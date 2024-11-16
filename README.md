# RPG - Dragon Repeller

## Project Overview

**RPG - Dragon Repeller** is a browser-based, interactive RPG game where the player navigates through different locations, fights monsters, and makes strategic decisions to defeat the final boss—a dragon that prevents townsfolk from escaping. This project is ideal for beginners who want to explore HTML, CSS, and JavaScript by creating an engaging and dynamic web game.

### Features

- Interactive game controls for navigation, fighting, and item management.
- Combat mechanics involving health, experience points (XP), and gold.
- A selection of weapons with different power levels and durability.
- Multiple locations including a town square, store, and cave.
- Varied enemies with distinct levels of difficulty.
- Game win/loss conditions and restart options.
- Secret Easter Egg game for additional fun.

## Table of Contents

- [Getting Started](#getting-started)
- [Game Structure](#game-structure)
- [Installation](#installation)
- [Game Mechanics](#game-mechanics)
- [How to Play](#how-to-play)
- [Project Structure](#project-structure)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with **RPG - Dragon Repeller**, you only need a web browser and a text editor if you wish to modify the code. Follow the instructions below to set up the game locally.

### Prerequisites

Ensure that you have:
- A modern web browser (e.g., Chrome, Firefox, Edge).
- Basic understanding of HTML, CSS, and JavaScript (optional for modification).

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/dragon-repeller.git
   cd dragon-repeller
   ```

2. **Open the Project**:
   Navigate to the project folder and open `index.html` in your web browser to play the game.

## Game Structure

### Core Files

- **`index.html`**: The main HTML structure of the game.
- **`styles.css`**: Contains the styling for the game interface.
- **`script.js`**: The main JavaScript file, which includes game logic and interactions.

### Game Elements

- **HTML**:
  - `#stats` displays player stats (XP, health, and gold).
  - `#controls` provides game interaction buttons.
  - `#monsterStats` displays current monster information during a fight.
- **CSS**:
  - Custom styles for buttons, game area, and text to ensure a visually appealing interface.
- **JavaScript**:
  - Manages player actions, combat mechanics, game state updates, and inventory management.

## Game Mechanics

### Locations

- **Town Square**: The starting location. Players can choose to visit the store, explore the cave, or face the dragon.
- **Store**: Players can buy health and new weapons using gold.
- **Cave**: Home to weaker monsters such as the "slime" and the "fanged beast."
- **Fight Area**: Where battles take place, and decisions like attacking or dodging can be made.

### Weapons and Inventory

- Players start with a basic weapon, the **stick**, and can upgrade to stronger weapons such as a **dagger**, **claw hammer**, and **sword**.
- Weapons can break during combat, adding a strategic layer to the game.

### Monsters

- **Slime** (Level 2, Health 15)
- **Fanged Beast** (Level 8, Health 60)
- **Dragon** (Level 20, Health 300)

Each monster presents different challenges based on its health and level.

### Combat System

- Players can **attack**, **dodge**, or **run** during battles.
- Combat damage is calculated based on the player's weapon power, XP, and a randomized hit chance.

### Winning and Losing

- **Victory**: Defeating the dragon ends the game with a win message.
- **Defeat**: If the player's health drops to zero, the game is lost, prompting a restart.

## How to Play

1. Choose an action using the buttons:
   - Go to different locations like the **store** or **cave**.
   - Fight enemies by clicking the appropriate buttons when in combat.
2. Manage your resources:
   - Earn gold and XP by defeating monsters.
   - Purchase weapons and health to improve your combat readiness.
3. Face the **dragon** in the final battle to win the game.
4. Explore the hidden **easter egg** game for extra challenges.

## Project Structure

```plaintext
dragon-repeller/
│
├── index.html      # Main game interface
├── styles.css      # Game styling
└── script.js       # Game logic and interactions
```

## Customization

### Modifying Game Elements

- **Weapons**: Add or modify weapon properties in the `weapons` array within `script.js`.
- **Monsters**: Edit or add monsters in the `monsters` array to change difficulty.
- **Locations**: Customize game locations and their descriptions in the `locations` array.

### CSS Styling

Adjust `styles.css` to change the appearance of the game interface, colors, button styles, and more.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to your branch: `git push origin feature-name`.
5. Submit a pull request.


---

Enjoy playing **RPG - Dragon Repeller** and feel free to share your feedback or contributions!
