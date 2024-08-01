<h1 align="center">
  <a href="https://github.com/Betim-Hodza/Swift-Simpson-Trapazoid-rule">
    <!-- Please provide path to your logo here -->
    <img src="docs/images/logo.svg" alt="Logo" width="100" height="100">
  </a>
</h1>

<div align="center">
  Swift-Simp-Trap-Rules
  <br />
  <a href="#about"><strong>Explore the screenshots »</strong></a>
  <br />
  <br />
  <a href="https://github.com/Betim-Hodza/Swift-Simpson-Trapazoid-rule/issues/new?assignees=&labels=bug&template=01_BUG_REPORT.md&title=bug%3A+">Report a Bug</a>
  ·
  <a href="https://github.com/Betim-Hodza/Swift-Simpson-Trapazoid-rule/issues/new?assignees=&labels=enhancement&template=02_FEATURE_REQUEST.md&title=feat%3A+">Request a Feature</a>
  .
  <a href="https://github.com/Betim-Hodza/Swift-Simpson-Trapazoid-rule/issues/new?assignees=&labels=question&template=04_SUPPORT_QUESTION.md&title=support%3A+">Ask a Question</a>
</div>

<div align="center">
<br />

[![Project license](https://img.shields.io/github/license/Betim-Hodza/Swift-Simpson-Trapazoid-rule.svg?style=flat-square)](LICENSE)

[![Pull Requests welcome](https://img.shields.io/badge/PRs-welcome-ff69b4.svg?style=flat-square)](https://github.com/Betim-Hodza/Swift-Simpson-Trapazoid-rule/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22)
[![code with love by Betim-Hodza](https://img.shields.io/badge/%3C%2F%3E%20with%20%E2%99%A5%20by-Betim-Hodza-ff1414.svg?style=flat-square)](https://github.com/Betim-Hodza)

</div>

<details open="open">
<summary>Table of Contents</summary>

- [About](#about)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Roadmap](#roadmap)
- [Support](#support)
- [Project assistance](#project-assistance)
- [Contributing](#contributing)
- [Authors & contributors](#authors--contributors)
- [Security](#security)
- [License](#license)
- [Acknowledgements](#acknowledgements)

</details>

---

## About

<table><tr><td>

> The swift version of Simpsons and trapezoidal numerical integration, prevously made in C.
> This uses NSExpression from Apple's Foundation Library to handle user input of mathmatical functions.

<details>
<summary>Screenshots</summary>
<br>

> **[?]**
> Please provide your screenshots here.

|                               Home Page                               |                               Login Page                               |
| :-------------------------------------------------------------------: | :--------------------------------------------------------------------: |
| <img src="docs/images/image.png" title="Simpsons" width="100%"> | <img src="docs/images/image-1.png" title="trapezoid" width="100%"> |

</details>

</td></tr></table>

### Built With

> Swift, Foundation, and NSExpression

## Getting Started

### Prerequisites

> swiftc, Foundation, NSExpression

### Installation

> to install run the command

``` git clone https://github.com/Betim-Hodza/Swift-Simpson-Trapaziod-rules.git ```

then cd NumericalIntegration, and run

```
swiftc main.swift
./swift
```

## Usage

- This program asks for user input on the number of intervals, the upper and lower bounds, and the function, and which approximation method to use.
- Depending on what the user chooses, program will approximate with either simpsons or trapezoidal rule, and parse through the function using tinyexpr library
- The program supports 
  - e.g. x + x * x // to mimick x^2 (doesn't us)
  - (x * 5) * 2 
  - (x * 5) / 2 

## Project assistance

If you want to say **thank you** or/and support active development of Swift-Simp-Trap-Rules:

- Add a [GitHub Star](https://github.com/Betim-Hodza/Swift-Simpson-Trapazoid-rule) to the project.

## Authors

The original setup of this repository is by [Betim Hodza](https://github.com/Betim-Hodza).

For a full list of all authors and contributors, see [the contributors page](https://github.com/Betim-Hodza/Swift-Simpson-Trapazoid-rule/contributors).

## License

This project is licensed under the **MIT license**.

See [LICENSE](LICENSE) for more information.

## Sources
NSExpression Guide
https://medium.com/@elifedman/understanding-nsexpression-in-swift-a-beginners-guide-50b7baa36271
