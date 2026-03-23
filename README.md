# Logic Grid

> Grid based Boolean logic puzzle game built with HTML5, CSS3, and vanilla JavaScript.

[![HTML5](https://img.shields.io/badge/HTML5-Canvas orange?style=flat square&logo=html5)](https://html.spec.whatwg.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript ES6-yellow?style=flat square&logo=javascript)](https://developer.mozilla.org/en US/docs/Web/JavaScript)
[![CSS3](https://img.shields.io/badge/CSS3-Responsive blue?style=flat square&logo=css3)](https://www.w3.org/Style/CSS/)

---

## Overview

Logic Grid is an educational puzzle game that challenges players to solve Boolean logic problems on a grid based interface. Built entirely with vanilla JavaScript and HTML5, this game requires strategic thinking and logical reasoning to match all constraints and win. Perfect for computer science students and logic enthusiasts, Logic Grid provides an engaging way to practice Boolean algebra concepts.

The game features procedurally generated puzzles with progressive difficulty, real-time constraint validation, a polished dark interface, and immediate visual feedback. Players must carefully plan their moves to satisfy all logical conditions simultaneously, introducing various logic gate operations as difficulty increases.

---

## Features

- 5x5 grid based puzzle interface
- Three tile states: ON (yellow), OFF (gray), UNKNOWN
- Progressive difficulty with escalating logic operations:
  - Levels 1-3: Basic TOGGLE logic
  - Levels 4-6: OR gate logic
  - Levels 7-9: XOR gate logic
  - Level 10+: Mixed AND/OR/XOR/NOT operations
- Real-time constraint validation
- Move counter and restart functionality
- Win condition detection with animated overlay
- Visual gate operation indicators
- Animated particle background via Canvas 2D
- Dark themed responsive design
- Toggleable help panels with keyboard support
- Accessible high contrast interface

---

## Screenshots

> Drop screenshots into `screens/` or the root and they'll render here.

![Logic Grid Game](screens/logicgrid.png)

---

## Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required

### Play Online

Visit the live game at: https://logicgrid by naadir.netlify.app/

### Local Development

```bash
git clone https://github.com/Naadir-Dev-Portfolio/HTML5-Game-LogicGrid.git
cd HTML5-Game-LogicGrid
# Open index.html in your web browser
python -m http.server 8000  # Or use any local server
```

Then navigate to `http://localhost:8000` in your browser.

---

## Tech Stack

- HTML5 Canvas, 2D graphics and animated background
- CSS3, Responsive grid layout, animations, and styling
- Vanilla JavaScript (ES6), Game logic and puzzle generation
- Netlify, Cloud deployment

---

## How It Works

The game presents a grid of cells where each can be toggled between ON, OFF, and UNKNOWN states. Players receive logical constraints for each tile (e.g., "this cell must be ON if its neighbor is OFF"). The goal is to set all cells to their correct states while satisfying every constraint. As difficulty increases, the logic gates applied become more complex, introducing OR, XOR, AND, and NOT operations that affect neighboring tiles.

---

## How to Play

1. Click on grid tiles to cycle through states: ON → OFF → UNKNOWN
2. Read the logic constraints carefully
3. Figure out which tiles must be ON and which must be OFF
4. When all constraints are satisfied, you win and advance to the next level
5. Use "Restart" to reset the current puzzle and try again
6. Watch the logic tier increase as you progress through levels

---

## Related Projects

- [HTML5-Game Algebraverse](https://github.com/Naadir Dev Portfolio/HTML5-Game Algebraverse)
- [HTML5-Game Hexamatch](https://github.com/Naadir Dev Portfolio/HTML5-Game Hexamatch)
- [HTML5-Game RainDrops](https://github.com/Naadir Dev Portfolio/HTML5-Game RainDrops)
