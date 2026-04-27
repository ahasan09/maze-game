# Maze Game

A browser-based maze game where you navigate a player from the start (`S`) to the finish (`F`) using arrow keys, avoiding walls (`W`).

## How to Play

- Use the **Arrow Keys** to move the player
- Avoid walls (`W`)
- Reach the `F` cell to win

## Running

No installation needed. Open `index.html` directly in any modern browser:

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

Or serve with a local server:

```bash
npx serve .
```

Then open [http://localhost:3000](http://localhost:3000).

## Prerequisites

- Any modern web browser (Chrome, Firefox, Edge, Safari)

## Project Structure

```
maze-game/
├── index.html   # Entry point
├── index.js     # Game logic — map rendering, movement, collision detection
├── style.css    # Grid and player styles
└── assets/      # Images and other assets
```
