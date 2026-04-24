# Tetris Rain Animation

A simple, lightweight Tetris-style rain animation built with HTML, CSS, and JavaScript.

<p align="center">
  <img src="./Screenshot%202024-07-26%20003537.png" alt="Tetris Rain Animation Screenshot" width="700" />
</p>

## About

This repository contains a small browser animation that mimics Tetris pieces falling like rain across the screen. It's intended as a fun visual demo and a starting point for experimenting with canvas animations and simple physics in JavaScript.

## Features

- Colorful Tetris-like pieces that fall from the top of the viewport
- Smooth animation implemented with requestAnimationFrame
- Configurable speed, size, and spawn rate in `script.js`
- Zero dependencies — just plain HTML, CSS, and JavaScript

## Demo

To view the animation, open `index.html` in your browser. For best results, open it in a modern desktop browser.

## Run locally

1. Clone the repository:

   git clone https://github.com/BinaryVortex/Tetris-Rain-Animation.git
   cd Tetris-Rain-Animation

2. Open `index.html` in your browser (double-click or use your browser's File > Open option), or serve it with a simple HTTP server:

   - Python 3:
     python -m http.server 8000
     Then open http://localhost:8000 in your browser.

   - Node (http-server):
     npx http-server . -p 8000
     Then open http://localhost:8000 in your browser.

## Customize

- Edit `script.js` to change the drop speed, piece sizes, colors, and spawn frequency.
- Edit `style.css` to change the page background and layout.

## File structure

- `index.html` — Entry point and canvas container
- `style.css` — Basic styles for the demo
- `script.js` — Main animation logic
- `Screenshot 2024-07-26 003537.png` — Example screenshot used in this README

## Built with

- JavaScript
- HTML
- CSS

## Contributing

Contributions, suggestions, and improvements are welcome. If you'd like to contribute, open an issue or submit a pull request with a clear description of the change.

## License

This repository does not currently include a license. If you want to permit others to use and contribute to your code, consider adding an open-source license (for example, MIT). If you want me to add a license file, tell me which license you'd like.

---

Made with ❤️ by BinaryVortex
