# 🔢 Web Calculator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub last commit](https://img.shields.io/github/last-commit/ChiragBorse/webcalculator1)](https://github.com/ChiragBorse/webcalculator1/commits/main)
[![GitHub repo size](https://img.shields.io/github/repo-size/ChiragBorse/webcalculator1)](https://github.com/ChiragBorse/webcalculator1)

## 🌟 Overview

`webcalculator1` is a simple, intuitive web-based calculator designed for basic arithmetic operations. It provides a clean user interface, making it easy for anyone to perform calculations directly in their browser. This project serves as a foundational example of building interactive web applications using standard front-end technologies.

**Key Value Proposition:**
*   **Simplicity:** A straightforward interface for quick calculations.
*   **Accessibility:** Works directly in any modern web browser without installation.
*   **Educational:** An excellent starting point for understanding front-end development principles.

**Target Audience:**
*   Users needing a quick, accessible calculator.
*   Beginner web developers looking for a practical project example.

**Current Status:** Stable - Version 1.0.0

## ✨ Features

*   **Basic Arithmetic Operations:** Perform addition, subtraction, multiplication, and division.
*   **Clear Functionality:** Easily clear the current input or the entire calculation.
*   **Decimal Support:** Handle floating-point numbers for precise calculations.
*   **Responsive Design:** Adapts to different screen sizes (though primarily designed for desktop).
*   **User-Friendly Interface:** Large, clickable buttons and a clear display.

## 🛠️ Tech Stack

This project is built using fundamental web technologies:

*   **HTML5:** For structuring the calculator's layout and content.
*   **CSS3:** For styling the calculator, ensuring a clean and modern look.
*   **JavaScript (ES6+):** For implementing the core calculator logic, handling user input, and performing calculations.

## 🏗️ Architecture

The project follows a simple client-side architecture, consisting of a single HTML file that integrates CSS for styling and JavaScript for interactivity.

```
.
├── Index.html          # Main entry point: Contains HTML structure, CSS styles, and JavaScript logic.
└── README.md           # Project documentation.
```

*   **`Index.html`**: This file is the heart of the application. It defines the calculator's display, buttons, and overall layout. It also embeds the CSS rules for styling and the JavaScript code for handling user interactions and calculations.
    *   **HTML Structure**: Defines the calculator container, display area, and button grid.
    *   **CSS Styling**: Embedded `<style>` tags or linked stylesheet (assumed embedded for simplicity) to define button appearance, layout, and responsiveness.
    *   **JavaScript Logic**: Embedded `<script>` tags (assumed at the end of `<body>`) to:
        *   Listen for button clicks.
        *   Update the display.
        *   Store numbers and operators.
        *   Perform arithmetic operations.
        *   Handle edge cases like division by zero or multiple decimal points.

## 🚀 Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You only need a modern web browser to run this calculator.
*   Google Chrome
*   Mozilla Firefox
*   Microsoft Edge
*   Safari

### Installation

There are no complex installation steps. You can run this project directly from your file system.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/ChiragBorse/webcalculator1.git
    ```
2.  **Navigate into the project directory:**
    ```bash
    cd webcalculator1
    ```
3.  **Open the `Index.html` file:**
    Simply double-click on `Index.html` in your file explorer, or open it via your browser's file menu (`File > Open File...`).

    The calculator should now be visible and interactive in your browser.

### Configuration

This project does not require any specific configuration files or environment variables as it's a client-side application.

## 💡 Usage

Using the web calculator is straightforward:

1.  **Input Numbers:** Click the number buttons (0-9) to enter digits into the display.
2.  **Perform Operations:** Click an operator button (+, -, \*, /) after entering the first number.
3.  **Continue Input:** Enter the second number.
4.  **Get Result:** Click the `=` (equals) button to see the result of the calculation.
5.  **Clear Entry (CE):** If available, this clears the last entered number.
6.  **All Clear (AC):** Clears the entire display and resets the calculator.
7.  **Decimal Point:** Use the `.` button to enter decimal numbers.

**Example:**
To calculate `12.5 + 7`:
1.  Click `1`, then `2`, then `.`, then `5`.
2.  Click `+`.
3.  Click `7`.
4.  Click `=`.
The display should show `19.5`.

## ⚙️ Development

To contribute or modify the calculator, you'll primarily be working with the `Index.html` file.

### Setting up Development Environment

1.  Open `Index.html` in your preferred code editor (e.g., VS Code, Sublime Text).
2.  Open `Index.html` in a web browser.
3.  Use your browser's developer tools (usually F12 or right-click -> Inspect) to inspect elements, debug JavaScript, and modify CSS in real-time.

### Running Tests

This project does not currently include automated tests. Manual testing by interacting with the calculator in the browser is the primary method for verification.

### Code Style Guidelines

*   **HTML:** Semantic HTML5 structure.
*   **CSS:** Keep styles organized and readable. Prefer descriptive class names.
*   **JavaScript:** Follow modern JavaScript best practices, use `const` and `let`, and comment complex logic.

## 🚀 Deployment

Deploying this web calculator is as simple as hosting the `Index.html` file on any static web server.

1.  **Static Hosting:** Upload the `Index.html` file to a service like GitHub Pages, Netlify, Vercel, or any web server (e.g., Apache, Nginx).
2.  **Local Server:** For local testing, you can use a simple Python HTTP server:
    ```bash
    python -m http.server 8000
    ```
    Then, open `http://localhost:8000/Index.html` in your browser.

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

Please ensure your pull requests are well-documented and your code adheres to the existing style.

## ❓ Troubleshooting

*   **Calculator not appearing:** Ensure you've opened `Index.html` directly in your browser. Check the browser's developer console (F12) for any JavaScript errors.
*   **Incorrect calculations:** Double-check your JavaScript logic, especially operator precedence and type conversions.
*   **Styling issues:** Use the browser's element inspector to check if CSS rules are being applied correctly and if there are any conflicting styles.

## 🗺️ Roadmap

*   Add more advanced mathematical functions (e.g., square root, percentage, trigonometry).
*   Implement keyboard support for input.
*   Add a history log of calculations.
*   Improve error handling and display for invalid operations.
*   Enhance responsiveness for mobile devices.

## 📄 License & Credits

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/licenses/MIT) file for details.

**Author:**
*   Chirag Borse

**Acknowledgments:**
*   Inspired by countless online calculator tutorials and examples.