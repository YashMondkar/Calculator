# Calculator (HTML • CSS • JavaScript)

A simple, responsive calculator built with vanilla JavaScript and a clean UI.

## Features
- Basic operations: add, subtract, multiply, divide
- Decimal input support
- `AC` (all clear) and `DEL` (delete last digit)
- Responsive layout (works on mobile screens)

## Tech Stack
- `index.html` – UI markup
- `style.css` – styling (grid layout + responsive rules)
- `script.js` – calculator logic (class-based) + button event handling

## Getting Started (Run Locally)
1. Clone this repo
2. Open `index.html` in your browser  
   - Optional: use VS Code **Live Server** for auto-reload

## Project Structure
- `index.html`
- `style.css`
- `script.js`
- `README.md`

## Notes / Known Issue
If the multiply/divide buttons show as `Ã—` / `Ã·` (or those operations don’t work), it’s an encoding/symbol mismatch between the button labels in `index.html` and the operator cases in `script.js`. Fix by using consistent symbols (e.g., `×` and `÷`) or use plain `*` and `/` in both UI and code.

## Deploy (GitHub Pages)
- Push to GitHub
- Go to **Settings → Pages**
- Select the branch and root folder
- Your site will be hosted and will load `index.html`

## License
Add a license if you want (e.g., MIT).
