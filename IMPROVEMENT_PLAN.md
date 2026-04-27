# Improvement Plan: maze_game

## Overview
Simple browser maze game with plain HTML/JS/CSS. No mobile support, no levels, no score tracking, and no save state.

## Improvements

### Core Gameplay
- Add multiple levels with increasing complexity (larger mazes, more walls, moving obstacles)
- Add a maze generator algorithm (Recursive Backtracker or Prim's) to generate random mazes procedurally
- Add a timer and move counter per level
- Add a best-time leaderboard stored in localStorage

### Mobile Support
- Add touch/swipe controls for mobile devices (currently only arrow keys work)
- Add on-screen D-pad buttons as a fallback for touch devices
- Make the maze responsive — scale to fit the viewport on all screen sizes

### Code Quality
- Separate game logic from DOM manipulation into distinct modules
- Convert to TypeScript for type-safe maze state and player position
- Add ESLint + Prettier
- Add Jest unit tests for the maze generation and pathfinding logic

### Visual & UX
- Replace DOM-based rendering with HTML5 Canvas for smoother animations and better performance
- Add smooth player movement animation instead of instant teleport
- Add sound effects (optional, toggleable)

### DevOps
- Add Vite for bundling and a dev server with hot reload
- Add GitHub Actions CI: lint + test + build
- Deploy to GitHub Pages
