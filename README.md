# Jandave Calc 1 🧮

A scientific calculator built with a natural display (2D) interface, similar to Casio's Natural Display system. It supports LaTeX-style math rendering and real-time expression evaluation.

## Features

- Natural 2D math display (fractions, exponents, roots) powered by [KaTeX](https://katex.org/)
- Scientific calculation engine powered by [math.js](https://mathjs.org/)
- Shift / Alpha / Mode indicators like a real physical calculator
- Responsive UI styled with Tailwind CSS
- Runs entirely in the browser — no backend required

## Tech Stack

- HTML / CSS / JavaScript
- [Tailwind CSS](https://tailwindcss.com/) (via CDN)
- [KaTeX](https://katex.org/) for math rendering
- [math.js](https://mathjs.org/) for expression parsing and evaluation

## Status

🚧 **In active development.** Core calculator functions work, and I'm continuing to add more scientific/graphing features over time.

## Live Demo

[https://jandave.vercel.app/](https://jandave.vercel.app/)

## Repository

[https://github.com/jandavevidallo-spec/Hello-Im-Testing](https://github.com/jandavevidallo-spec/Hello-Im-Testing)

## Development Notes

I used AI assistance (Claude) to help with parts of this project — particularly wiring up KaTeX rendering and speeding up math.js integration. I reviewed, tested, and understand the logic behind the code; AI was used as a tool to move faster on well-solved problems (like math parsing) so I could focus more on the calculator's design and functionality.

Built and tested entirely on an Android device.

## How It Works

- **Input** is captured from on-screen key taps and displayed in real time.
- **math.js** parses the expression string and evaluates it (handling operator precedence, functions like `sin`/`log`, etc.) instead of writing a parser from scratch.
- **KaTeX** takes the expression and renders it as proper 2D math notation (fractions, exponents, roots) instead of plain text.
- UI state (Shift/Alpha/Mode/Angle indicators) is tracked with simple JS variables and toggled on tap, mimicking a real calculator's behavior.

## Getting Started

Clone the repo and open `index.html` in your browser — no build step required.

\```bash
git clone https://github.com/jandavevidallo-spec/Hello-Im-Testing.git
cd Hello-Im-Testing
open index.html
\```

## Roadmap

- [ ] 25+ digit precision
- [ ] more functions

## Author

Built by Jan Dave R. Vidallo — grade 10 student learning software engineering.
