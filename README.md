# Snake Game 🐍

A retro-styled modern, browser-based Snake game built with HTML5 Canvas and vanilla JavaScript — no frameworks, no dependencies.

## 🎮 Live Demo

Play it here: **[https://pronob155.github.io/Snake-game/](https://pronob155.github.io/Snake-game/)**

## Features

- **Single Player** — classic Snake with a scoring system and best-score tracking (saved locally in your browser)
- **Progressive difficulty** — the snake speeds up gradually as your score increases, instead of jumping suddenly
- **Online Multiplayer (2 players, separate devices)** — one player creates a room and shares a 4-digit code, the other joins from their own device/browser to play head-to-head in real time
- **3-2-1 countdown** before every match starts (single player and multiplayer)
- **Keyboard controls** — Arrow keys or WASD
- **Touch controls** — on-screen buttons and swipe gestures for mobile
- **Responsive design** — scales to fit any screen size

## How to Play

1. Choose **১ জন (Single Player)** or **২ জন (Multiplayer)** mode
2. **Single player:** press Start, wait for the countdown, then steer the snake with arrow keys / WASD / swipe to eat food and grow
3. **Multiplayer:**
   - Player 1 clicks **রুম তৈরি করো (Create Room)** and shares the generated code
   - Player 2 enters the code and clicks **রুমে যোগ দাও (Join Room)**
   - Once connected, the countdown starts automatically and both players control their own snake
4. Avoid hitting the walls, your own body, or (in multiplayer) the other snake

## Tech Stack

- HTML5 Canvas for rendering
- Vanilla JavaScript (no external libraries)
- `localStorage` for best-score persistence
- Shared key-value storage for syncing multiplayer state between devices

## Running Locally

Just open `index.html` (or the game file) in any modern browser — no build step or server required.

## License

Feel free to fork, modify, and use this project for learning or personal purposes.
