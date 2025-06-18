# Calculator iPhone

A responsive, web-based iPhone-style calculator built with plain HTML, CSS and JavaScript. This project reproduces the look-and-feel and basic behavior of the iPhone calculator UI while remaining lightweight and easy to run in any modern browser.

## Preview

![Calculator iPhone Preview](https://github.com/mihaiapostol14/Calculator-iPhone/blob/11554a0fd4bed20a3c81363b5d5d65de82213d79/assets/preview.png)

## Table of contents
- [Calculator iPhone](#calculator-iphone)
  - [Preview](#preview)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
  - [Technologies used](#technologies-used)
  - [Features](#features)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Project structure](#project-structure)
  - [Contributing](#contributing)
  - [License](#license)
  - [Author](#author)

## Overview
This repository contains a small client-side application that implements a calculator interface inspired by the iPhone. The app uses semantic HTML for structure, CSS for layout and visual styling (including a responsive, phone-like layout), and JavaScript to implement calculator logic and user interactions.

## Technologies used
- HTML
  - Provides the semantic page structure and calculator elements (display, buttons, container).
  - Accessible elements (buttons / ARIA attributes) can be added or improved as needed.
- CSS
  - Implements the visual design, colors, spacing and responsive layout to mimic an iPhone calculator.
  - Uses flexbox/grid and media queries to keep the UI usable on different screen sizes.
  - May include CSS variables for easily adjusting theme colors and spacing.
- JavaScript
  - Handles user input, arithmetic operations, expression parsing/formatting, and updating the display.
  - Implements button event handlers, keyboard support (optional), and state management for the calculator.

## Features
- iPhone-like visual design and responsive layout
- Basic arithmetic operations (addition, subtraction, multiplication, division)
- Clear / All Clear functionality
- Decimal input support
- Keyboard input support (if implemented)
- Lightweight: no build tools or dependencies required

## Installation
Clone the repository and change into the project directory:

```bash
git clone https://github.com/mihaiapostol14/Calculator-iPhone.git
cd Calculator-iPhone
```

After cloning:
- Open `index.html` in your browser (double-click the file or run a local static server).
- Optionally, run a simple static server (for example `npx serve` or `python -m http.server`) to serve the files over localhost.

## Usage
- Click the calculator buttons or use your keyboard (if keyboard support is available) to enter numbers and operations.
- Results are shown in the display area at the top of the calculator.
- Use the clear (C / AC) button to reset the current input or all state.

## Project structure
A typical layout for this repo:
- index.html — main HTML file containing the calculator markup
- css/
  - styles.css — visual styling and responsive rules
- js/
  - app.js — calculator logic and event handling
- assets/ — (optional) images, icons, or fonts used by the UI

## Contributing
Contributions are welcome. Suggested improvements:
- Add more operations (percentage, ± toggle, memory functions)
- Improve accessibility (aria-labels, focus management)
- Add unit tests for the calculation logic
- Add packaging or deployment scripts

If you plan to contribute:
1. Fork the repository
2. Create a feature branch
3. Open a PR with a clear description of the change

## License
Include your chosen license here (for example MIT). If no license file is present, add one before distributing or using the code in other projects.

## Author

[Mihai Apostol](https://github.com/mihaiapostol14)
