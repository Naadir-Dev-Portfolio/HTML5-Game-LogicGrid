# Logic Grid

**Logic Grid** is a browser-based puzzle game designed to teach basic Boolean logic and digital circuit thinking through interactive grid puzzles.

## Description

- **Grid Mechanics**  
  Toggle lights on a 5×5 grid; each click applies Boolean logic to the selected tile and its orthogonal neighbors.
- **Progressive Logic Gates**  
  - Levels 1–3: Basic TOGGLE (Lights-Out style)  
  - Levels 4–6: OR logic  
  - Levels 7–9: XOR logic  
  - Level 10+: Mixed AND/OR/XOR/NOT per tile  
- **Objective**  
  Turn **all** lights **OFF** in as few moves as possible. On success, you advance to more challenging logic tiers.

Author
Naadir – created with AI-assisted coding (GPT-4o) under my direction and supervision.
Demonstrates end-to-end design and delivery of an interactive, educational web application.

Features

## Features

- Infinite levels with rising difficulty
- Move counter and restart button
- Visual gate indicators (first letter of gate)
- Animated “Level Complete!” overlay
- Subtle Canvas 2D bubble background
- Responsive layout for desktop & mobile
- Accessible: keyboard & high-contrast friendly

## Tech Stack

- **HTML5 & CSS3** (Flexbox, Grid, custom properties, transitions)  
- **Vanilla JavaScript (ES6)** – no frameworks or build tools  
- **Canvas 2D** for the animated background  
- **Local state only**; runs by opening `index.html` in any modern browser

## Installation & Usage

1. **Download** or **clone** this repository.  
2. Open **`index.html`** in Chrome, Firefox, Safari, or Edge.  
3. Click tiles to solve puzzles.  
4. Use **Restart** to reset the current level.  

Enjoy learning Boolean logic in a fun, hands-on way!
