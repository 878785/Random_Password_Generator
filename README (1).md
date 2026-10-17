<div align="center">

# Random Password Generator

**A clean, responsive web tool for generating customizable passwords.**

Built with HTML, CSS, and JavaScript.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Open%20App-635BFF?style=for-the-badge)](https://878785.github.io/Random_Password_Generator/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

[**Launch the application →**](https://878785.github.io/Random_Password_Generator/)

</div>

---

## Overview

Random Password Generator is a lightweight browser-based utility that lets users create passwords based on their preferred length and character sets. The interface is designed to be straightforward, responsive, and easy to use across different screen sizes.

## Features

- **Adjustable length** — choose a password length between 4 and 32 characters.
- **Custom character sets** — select uppercase letters, lowercase letters, numbers, and symbols.
- **Copy to clipboard** — quickly copy the generated password.
- **Strength feedback** — view an estimated password-strength indicator.
- **Responsive interface** — a dark, modern layout for desktop and mobile screens.

> Feature availability depends on the implementation currently deployed to the live site.

## Live Demo

Try the deployed application:

**[https://878785.github.io/Random_Password_Generator/](https://878785.github.io/Random_Password_Generator/)**

## Preview

Add a screenshot of the application to the repository as `screenshot.png`, then uncomment the image below.

<!--
<p align="center">
  <img src="screenshot.png" alt="Random Password Generator interface" width="760">
</p>
-->

## Tech Stack

| Technology | Responsibility |
|---|---|
| HTML5 | Semantic page structure and controls |
| CSS3 | Layout, visual styling, and responsive design |
| JavaScript | Password-generation logic and UI interactions |
| Web Crypto API | Cryptographically strong random values, if used in the implementation |

## Getting Started

### Run locally

1. Clone this repository:

   ```bash
   git clone https://github.com/878785/Random_Password_Generator.git
   ```

2. Open the project directory:

   ```bash
   cd Random_Password_Generator
   ```

3. Open `index.html` in your browser, or use the Live Server extension in Visual Studio Code.

No build tools or package installation are required for a basic static version.

## Project Structure

```text
Random_Password_Generator/
├── index.html      # Application structure
├── style.css       # Styling and responsive layout
├── script.js       # Password generation and interactions
└── README.md       # Project documentation
```

## Security Notes

- Prefer the browser's **Web Crypto API** for security-sensitive random selection rather than `Math.random()`.
- Ensure the generator handles the case where no character sets are selected.
- A strength meter is an estimate, not a guarantee of security.
- Avoid storing or logging generated passwords unnecessarily.
- For production use, verify that character selection is unbiased and that generated passwords meet the selected options.

## Potential Enhancements

- Exclude ambiguous characters such as `O`, `0`, `I`, and `l`.
- Add an option to prevent repeated characters.
- Add a passphrase-generation mode.
- Improve accessibility with keyboard-friendly controls and clear status messages.
- Add automated tests for password length, character-set rules, and edge cases.
- Add a theme switcher.

## Learning Outcomes

This project is useful for practising:

- DOM selection and manipulation
- Event listeners and input handling
- JavaScript functions and string operations
- Random-value generation
- Responsive UI development
- Deploying a static website with GitHub Pages

## Contributing

Suggestions and improvements are welcome. To propose a change, fork the repository, create a feature branch, and open a pull request describing the update.

## License

No license has been specified yet. If you intend to allow reuse or contributions under open-source terms, add a `LICENSE` file and update this section accordingly.

---

<div align="center">

**Built as a hands-on web development project.**

[Live Demo](https://878785.github.io/Random_Password_Generator/) · [Repository](https://github.com/878785/Random_Password_Generator)

</div>
