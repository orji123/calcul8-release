# 🧾 Changelog

## Version 1.1.0 - Calculator Improvements

**Update focusing on calculator reliability and ranking system enhancements**

### 🐛 Bug Fixes

#### Calculator Operator Fixes
- **Factorial Operator (`!`)**: Fixed to insert the symbol at cursor position instead of auto-calculating immediately
- **Percent Operator (`%`)**: Fixed to insert the symbol at cursor position with proper conversion to `(number/100)` format
- **Negate Operator (`±`)**: Fixed toggle behavior with proper bracket insertion when negating after operators, preventing multiple minus signs
- **Percent with Parentheses**: Fixed expressions like `(50+10)%` to correctly calculate percentage of parenthesized expressions
- **Percent with Nested Parentheses**: Fixed complex expressions like `((10+5)+3)%` using iterative processing
- **Modulo Operator (`mod`)**: Fixed to work correctly with parentheses and proper space handling
- **Factorial with Parentheses**: Fixed expressions like `(5+3)!` to correctly evaluate factorial of parenthesized results
- **Nested Parentheses in Functions**: Fixed all scientific functions (sin, cos, tan, log, sqrt, abs, etc.) to correctly handle nested parentheses like `sin((10+5)×2)`

#### Calculator Display & Interaction Fixes
- **Error Handling**: Improved error display - expressions are now preserved on error, and "Error" is shown in red in the result field
- **Error State Management**: Errors now clear properly when user starts typing again
- **Pre-calculation Results**: Fixed scientific calculator to show live preview results instead of displaying `0` when idle
- **Cursor Positioning**: Fixed cursor to properly jump over multi-character operators (sin, cos, log, etc.) preventing cursor placement inside operators
- **Incomplete Expression Detection**: Improved detection of incomplete expressions (ending with operators) before evaluation

### ✨ New Features

#### Ranking System Enhancements
- **Expanded Ranking System**: Expanded from 7 to 10 ranks, adding 3 new ultimate ranks:
  - **Astra** (10,000,000 calculations)
  - **Aeternum** (100,000,000 calculations)
  - **Singularitas** (1,000,000,000 calculations)
- **Lore System**: Added narrative content that unlocks as you progress through ranks, telling the story of computational ascension
- **Rank Names Updated**: Improved rank naming for better progression narrative (Cogitatio, Artifex, Aetherius, etc.)

#### Theme & Customization
- **Pastel Theme Family**: Added 3 new pastel themes:
  - **Sky** (Soft cyan)
  - **Blossom** (Gentle magenta)
  - **Sunshine** (Warm yellow)
- **Custom Fonts**: Added support for multiple font families:
  - System Default
  - Curated Font Set using Orbitron, JetBrains Mono, Nunito and Rubik

### 🎯 Improvements

#### Calculator Functionality
- **Improved Operator Precedence**: Fixed order of operations for percent, modulo, and factorial
- **Better Live Preview**: Enhanced live calculation preview for expressions ending with percent
- **Enhanced Expression Parsing**: Improved handling of complex expressions with nested parentheses and mixed operators

#### User Experience
- **Preserved History**: All calculations are saved to history
- **Better Error Messages**: Clear error indication without clearing the expression
- **Smoother Interactions**: Improved cursor positioning and text editing experience

---

## Version 1.0.0 - Initial Release

**First public release of Calcul8**

### Included Features
- Perform simple and scientific calculations with ease
- Convert across 36+ categories, including length, weight, temperature and currency
- Access a built-in formula library for math, science, finance, and health
- Add and subtract time and convert dates to age with the time calculator
- Scale recipes with the cooking recipe modifier
- Convert text and code between different formats and encodings
- Use the app fully offline, with online sync only for ranks and updates
- Personalize your experience with minimalist, neon, and retro themes
- Earn badges and climb the global leaderboard as you calculate
- View your calculation history and review past calculations

