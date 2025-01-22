# Space Shooter Game

Space Shooter Game is a 2D space shooting game built using PIXI.js. The player controls a spaceship, shoots bullets to destroy meteors, and fights a boss at the second level.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Game Mechanics](#game-mechanics)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/space-shooter-game.git

2. Navigate to the project directory:

cd space-shooter-game

3. Install dependencies (if any):

npm install

Usage
Open index.html in your web browser to start the game.

Use the arrow keys to move the spaceship:

ArrowLeft: Move left
ArrowRight: Move right
Press the spacebar ( ) to shoot bullets.

Game Mechanics
Levels: The game has two levels. In the first level, the player must destroy meteors. In the second level, the player fights a boss.
Bullets: The player can shoot bullets to destroy meteors and the boss.
Boss: The boss appears in the second level and can shoot bullets at the player.
Health Bar: The boss has a health bar that decreases when hit by bullets.
Project Structure


space-shooter-game/
├── css/
│   └── styles.css
├── fonts/
│   └── PressStart.ttf
├── src/
│   ├── scripts/
│   │   ├── App.js
│   │   ├── Game.js
│   │   ├── Ship.js
│   │   ├── Meteor.js
│   │   └── Bullet.js
│   └── sprites/
│       ├── ship.png
│       ├── meteor.png
│       ├── boss.png
│       └── bg.png
├── index.html
└── README.md


Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

License
This project is licensed under the MIT License. See the LICENSE file for details.