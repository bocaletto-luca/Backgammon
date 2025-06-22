# Backgammon - Web Game
#### Author: Bocaletto Luca

[![Made with HTML5](https://img.shields.io/badge/Made%20with-HTML5-E34F26?logo=html5)](https://www.w3.org/html/)  
[![Made with CSS3](https://img.shields.io/badge/Made%20with-CSS3-1572B6?logo=css3)](https://www.w3.org/Style/CSS/)  
[![Made with JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-F7DF1E?logo=javascript)](https://developer.mozilla.org/docs/Web/JavaScript)    

[![Test Online](https://img.shields.io/badge/Test%20Online-Click%20Here-brightgreen?style=for-the-badge)](https://bocaletto-luca.github.io/Backgammon/)

**Backgammon - Single Player vs Bot (Full Rules)** is a modern, fully responsive web game that brings a simplified yet rich version of the classic Backgammon experience to your browser. In this implementation, you play as “White” against a Bot (“Black”) following nearly complete rules—including hitting, the Bar for checkers, re-entry mechanics, and bearing off.

> The project is implemented using HTML5, CSS3, and JavaScript. The game layout is split into three main parts:
>
> - Two Bar areas (one for each player) on the sides.
> - A central board divided into two rows (points 13–24 on top and points 12–1 on bottom).
>
> The game logic enforces that if you have checkers on the Bar, you must re-enter them first before making any other moves.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Developer](#developer)

---

## Overview

Backgammon is a game of strategy and chance. This web version allows you to play a full (albeit simplified) version of Backgammon against a Bot. The game includes:

- **Dice Rolling:** Roll two dice (with doubles giving four moves) to determine movement.
- **Checker Movement & Hitting:** Move your checkers according to standard rules. Landing on a point occupied by a single opponent checker sends that checker to the Bar.
- **Bar & Re-entry:** If you have checkers on the Bar, you must re-enter them using the dice before other moves.
- **Bearing Off:** When all your checkers are in your home board, you can bear them off.
- **Turn Management:** The game automatically switches turns between you (White) and the Bot (Black), with on-screen indicators.
- **Responsive Design:** Works on both desktop and mobile devices with a modern dark-themed interface.
- **Help Modal:** Built-in Help instructions guide players through the rules.

---

## Features

- **Full Game Mechanics:**  
  - Dice roll with doubles granting four moves.  
  - Legal moves calculation, including re-entry from the Bar.  
  - Hitting opponent checkers and sending them to the Bar.
  - Bearing off when eligible.

- **Bot Opponent:**  
  - The Bot selects random legal moves while respecting the rules regarding the Bar and hitting.
  
- **Responsive UI:**  
  - Two Bar areas are displayed at the sides of the board.  
  - The central board is divided into two rows, clearly displaying all checkers.
  
- **Modern and Clean Design:**  
  - Dark themed layout with smooth transitions and clear visual feedback.
  
- **Help Modal:**  
  - A built-in Help section explains the rules and how to play.

---

## Technologies Used

- **HTML5:** Structure and semantic markup.
- **CSS3:** Styling, responsive design (with Flexbox and media queries), and modern UI transitions.
- **JavaScript (ES6):** Game logic, event handling, and state management.

---

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/bocaletto-luca/Backgammon.git
2. Start WebServer and open index.html in Web Browser

## Usage
Starting a New Game: Click the New Game button to initialize the game with the standard Backgammon starting positions.

Rolling the Dice: Click Roll Dice to generate your dice values. The values show how many points you can move. If you roll doubles, you get four moves.

## Making a Move:

Click on a point that contains your checkers to move them.

If multiple moves are possible, a prompt will ask you to choose a die value.

If you have checkers on the Bar, you must re-enter them first using your dice.

Bot Turn: After you finish your moves, the Bot will automatically make its moves following the same rules.

Win Condition: The game ends when either you or the Bot bears off all 15 checkers.

Help: Click the Help button at the top right for detailed game instructions.

#### Enjoy Game, By Bocaletto Luca
 
#### License: GPLv3
