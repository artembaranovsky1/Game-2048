# Game 2048

A browser-based implementation of the classic **2048** puzzle game. Slide numbered tiles across a 4x4 grid, merge matching values, and try to reach the 2048 tile (or keep going beyond it!). The game tracks your score and lets you restart at any time.

## Live Preview

- [DEMO LINK](https://artembaranovsky1.github.io/Game-2048/)

## Technologies Used

- HTML5
- SCSS (Sass)
- JavaScript (ES6+, class-based game logic)
- [Parcel](https://parceljs.org/) — module bundler

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository:

```
git clone https://github.com/artembaranovsky1/Game-2048.git
cd Game-2048
```

2. Install dependencies:

```
npm install
```

3. Run the project locally:

```
npm start
```

The app will be available at the local address printed in your terminal (by default `http://localhost:1234`).

## Features

- Classic 4x4 sliding-tile 2048 gameplay
- Keyboard-controlled tile movement (arrow keys)
- Score tracking that updates as tiles merge
- Win and lose state messages
- Restart button to start a new game at any time
