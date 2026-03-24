# Calsii

![Calsii Logo](https://raw.githubusercontent.com/Akshay94os/Calculator/main/assets/calsii-banner.png) <!-- Placeholder for a project banner/logo -->

A sleek, responsive, and easy-to-use web-based calculator for everyday arithmetic.

[![Build Status](https://github.com/Akshay94os/Calculator/workflows/static/badge.svg)](https://github.com/Akshay94os/Calculator/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![GitHub Pages](https://img.shields.io/badge/Demo-Live-brightgreen)](https://akshay94os.github.io/Calculator/)
[![Issues](https://img.shields.io/github/issues/Akshay94os/Calculator)](https://github.com/Akshay94os/Calculator/issues)

## Overview

Calsii is a simple yet elegant web calculator designed to perform basic arithmetic operations with ease. Built entirely with front-end technologies, it offers a clean user interface and a responsive design, making it accessible on various devices. It's perfect for quick calculations without the need for complex software.

## Features

*   **Basic Arithmetic Operations**: Perform addition, subtraction, multiplication, and division.
*   **Clear Functionality**: `C` (Clear Entry) to remove the last input and `AC` (All Clear) to reset the calculator.
*   **Responsive Design**: Adapts seamlessly to different screen sizes, from desktops to mobile phones.
*   **User-Friendly Interface**: Intuitive button layout for a smooth user experience.
*   **Decimal Support**: Handle calculations involving decimal numbers.

## Tech Stack

Calsii is built using standard web technologies:

*   **HTML5**: For the structural markup of the calculator interface.
*   **CSS3**: For styling, layout, and responsive design.
*   **JavaScript (ES6+)**: For implementing the calculator's logic and interactivity.

## Architecture

Calsii follows a client-side architecture, where all computation and rendering occur directly in the user's web browser.

*   **`index.html`**: The main entry point, containing the HTML structure of the calculator, embedded CSS for styling, and JavaScript for the core logic.
*   **Client-Side Logic**: JavaScript handles button clicks, input parsing, arithmetic operations, and updating the display. No server-side components or databases are involved.

## Getting Started

Follow these instructions to get a copy of Calsii up and running on your local machine.

### Prerequisites

To run Calsii, you only need a modern web browser.

*   Google Chrome (latest version recommended)
*   Mozilla Firefox (latest version recommended)
*   Microsoft Edge (latest version recommended)
*   Safari (latest version recommended)

### Installation

There are no complex installation steps. Calsii is a static web application.

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/Akshay94os/Calculator.git
    ```
2.  **Navigate into the project directory**:
    ```bash
    cd Calculator
    ```
3.  **Open `index.html`**:
    Simply open the `index.html` file in your preferred web browser. You can usually do this by double-clicking the file or by dragging it into an open browser window.

    ```bash
    # Example using a command-line utility (optional)
    open index.html # On macOS
    start index.html # On Windows
    xdg-open index.html # On Linux
    ```

### Configuration

No special configuration is required to run Calsii. All settings are embedded within the `index.html` file.

## Usage

Once you have opened `index.html` in your browser, you can start using Calsii immediately.

1.  **Input Numbers**: Click the number buttons (0-9) to input digits into the display.
2.  **Select Operations**: Click the operator buttons (+, -, \*, /) to perform arithmetic operations.
3.  **Calculate Result**: Click the `=` button to see the result of your calculation.
4.  **Clear Entry**: Use the `C` button to clear the last entered number or operation.
5.  **All Clear**: Use the `AC` button to clear the entire calculation and reset the display to `0`.

**Example Calculation**:

To calculate `12.5 + 7`:
1.  Click `1`, then `2`, then `.`, then `5`.
2.  Click `+`.
3.  Click `7`.
4.  Click `=`.
The display should show `19.5`.

## Development

If you wish to modify or contribute to Calsii, here's how to set up your development environment.

### Setting up Development Environment

1.  **Clone the repository** (if you haven't already):
    ```bash
    git clone https://github.com/Akshay94os/Calculator.git
    cd Calculator
    ```
2.  **Open in a Code Editor**: Open the `Calculator` directory in your favorite code editor (e.g., VS Code, Sublime Text).
3.  **Live Server (Optional but Recommended)**: For real-time updates as you code, install a "Live Server" extension in your editor (e.g., VS Code's Live Server extension) and open `index.html` with it. This automatically reloads the browser when you save changes.

### Running Tests

This project currently does not have automated tests. For development, manual testing by interacting with the calculator in the browser is the primary method.

### Code Style Guidelines

*   **HTML**: Semantic HTML5, well-indented.
*   **CSS**: Use descriptive class names, keep styles organized, prefer `flexbox` or `grid` for layout.
*   **JavaScript**: Follow modern JavaScript conventions, use `const` and `let`, keep functions small and focused.

## Deployment

Calsii is a static web application and can be easily deployed to various hosting services.

### GitHub Pages

This repository is configured to deploy automatically to GitHub Pages using the `.github/workflows/static.yml` workflow.

1.  Ensure your repository is public.
2.  Push your changes to the `main` branch.
3.  GitHub Actions will automatically build and deploy your site to `https://<YOUR_GITHUB_USERNAME>.github.io/Calculator/`.

### Other Static Hosting Services

You can deploy Calsii to any static web hosting service, such as Netlify, Vercel, or AWS S3 + CloudFront.
1.  Build your project (no build step for Calsii, just the `index.html` file).
2.  Upload the entire project directory (containing `index.html` and any assets) to your chosen hosting provider.

## Contributing

Contributions are welcome! If you have suggestions for improvements, new features, or bug fixes, please follow these steps.

1.  **Fork the repository**.
2.  **Create a new branch**: `git checkout -b feature/your-feature-name` or `bugfix/issue-description`.
3.  **Make your changes**: Implement your feature or fix the bug.
4.  **Commit your changes**: `git commit -m 'feat: Add new feature'` or `fix: Resolve bug in calculation`.
5.  **Push to your fork**: `git push origin feature/your-feature-name`.
6.  **Open a Pull Request**: Describe your changes clearly and link to any relevant issues.

Please ensure your code adheres to the existing style and functionality.

## Troubleshooting

*   **Calculator not responding**:
    *   Check your browser's developer console (F12) for any JavaScript errors.
    *   Ensure `index.html` is loaded correctly and all embedded scripts are running.
*   **Display issues**:
    *   Verify your browser's zoom level.
    *   Check for CSS errors in the developer console.
*   **Incorrect calculations**:
    *   Review the JavaScript logic for arithmetic operations.

If you encounter persistent issues, please open an issue on the [GitHub Issues page](https://github.com/Akshay94os/Calculator/issues).

## Roadmap

*   **Keyboard Support**: Allow users to input numbers and operations using their keyboard.
*   **Advanced Functions**: Add scientific calculator functions (e.g., square root, power, trigonometry).
*   **Calculation History**: Display a log of previous calculations.
*   **Memory Functions**: Implement M+, M-, MR, MC buttons.
*   **Theme Switching**: Offer light/dark mode or customizable themes.

## License & Credits

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Developed by**:
*   [Akshay94os](https://github.com/Akshay94os)

**Acknowledgments**:
*   Inspired by classic calculator designs.
*   Thanks to the open-source community for tools and resources.
*   Special thanks to GitHub for providing free hosting via GitHub Pages.