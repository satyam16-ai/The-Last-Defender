# The Last Defender

**The Last Defender** is a browser-based action game where players control a soldier defending a futuristic city from invading robots. The mission is to defeat enemy robots, collect passcode pieces hidden across levels, and reach the control room to shut down all hostile forces. Each level reveals a new part of the city and a part of the passcode, with progressively challenging gameplay.

## Game Concept

In **The Last Defender**, a soldier must navigate through a city under attack by rogue robots. Across 10 levels, the player fights off robots, avoids obstacles, and collects parts of a control room passcode. The ultimate goal is to gather all digits of the passcode to enter the control room and stop the robots for good.

## Features

- **Action-Packed Gameplay**: Navigate through a city filled with hostile robots, engaging in combat and collecting passcode fragments.
- **Progressive Levels**: Unlock new city zones and passcode pieces with each level.
- **Robot AI**: Each robot has different behaviors, adding variety and challenge to gameplay.
- **Mission Objective**: Gather all passcode digits to access the control room and disable the robots.

## Folder Structure

city-robot-game/
├── index.html               # Main HTML file to load the game
├── assets/                  # Folder for all game assets (images, sounds, etc.)
│   ├── images/              # Images for characters, robots, background, etc.
│   ├── sounds/              # Sound effects and background music
│   └── fonts/               # Custom fonts (if any)
├── css/                     # Stylesheets for the game
│   └── styles.css           # Main CSS file for game styling
├── js/                      # JavaScript files for game logic
│   ├── main.js              # Main game loop and initialization code
│   ├── player.js            # Player character logic (movement, shooting, etc.)
│   ├── enemy.js             # Robot/Enemy behavior and AI
│   ├── level.js             # Code for managing levels, layouts, and objectives
│   ├── ui.js                # UI components (health bar, passcode display, etc.)
│   └── utils.js             # Utility functions (collision detection, etc.)
└── data/                    # JSON files for storing game data and level configurations
    ├── levels.json          # Level-specific data (map layout, passcode, etc.)
    └── config.json          # General game settings and configurations


