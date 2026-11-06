# Bharat Ekta Yuva Chunav - Fighting Game

A web-based 2D fighting game featuring 8 Indian-themed characters with unique abilities. Play against the computer on PC or mobile devices.

## Features

- **8 Unique Characters** with distinct abilities:
  - **Ojas**: Body enlargement - increases damage and screen shakes when walking
  - **Divyansh**: Sound wave attack - damages opponent with laughter
  - **Ishan**: Gorilla transformation - increased speed and damage
  - **Aman**: Elongated arms - increased attack range
  - **Parth**: Flash step - high-speed dash mobility
  - **Kartikey**: Whip extension - ranged attacks with hair
  - **Anaraghya**: Muscular chicken transformation - high damage
  - **Sachit**: Boxing gear - highest damage attacks

- **Cross-platform Support**: Works on PC and mobile devices
- **Touch Controls**: Virtual joystick and attack buttons for mobile
- **Keyboard Controls**: WASD movement, J/K/L for attacks on PC
- **Balanced Gameplay**: Each character has strengths and weaknesses

## Controls

### PC
- **WASD**: Movement
- **J**: Light Attack
- **K**: Heavy Attack
- **L**: Special Ability
- **Escape**: Pause (future feature)

### Mobile
- **Virtual Joystick** (bottom-left): Movement
- **Light Attack (J)**: Light attack button
- **Heavy Attack (K)**: Heavy attack button
- **Special (L)**: Special ability button

## Game States

1. **Main Menu**: Start game
2. **Character Selection**: Choose your fighter
3. **Battle**: Fight against random AI opponent
4. **Results**: View round winner
5. **Game Over**: Final results

## Development

### Tech Stack
- HTML5 Canvas for rendering
- Vanilla JavaScript
- CSS for styling and responsive design
- Web Audio API for sound effects

### File Structure
```
/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Game styling
├── js/
│   ├── game.js         # Core game engine
│   ├── characters.js   # Character definitions
│   ├── combat.js       # Combat system
│   └── audio.js        # Sound system
└── README.md           # This file
```

### Running the Game

Open `index.html` in any modern web browser. No server required.

## Audio Design

The game features:
- Interactive sound effects for attacks, special abilities, and UI
- Musical tones using Web Audio API oscillators
- Unique sounds for each character's special ability

## Character Balance

| Character | Health | Speed | Base DMG | Special Ability |
|-----------|--------|-------|----------|-----------------|
| Ojas | 110 | Medium | 10 | Enlarge: +30% damage, screen shake |
| Divyansh | 100 | Medium | 10 | Sound wave: 15 damage range attack |
| Ishan | 95 | Fast | 12 | Gorilla: +50% damage when transformed |
| Aman | 100 | Medium | 10 | Elongate: +50% attack range |
| Parth | 105 | Very Fast | 5 | Flash: Instant dash |
| Kartikey | 95 | Medium | 11 | Whip: 13 damage, ranged |
| Anaraghya | 115 | Slow | 15 | Chicken: +50% damage when transformed |
| Sachit | 100 | Medium | 20 | Boxing: Highest damage |

## License

This is a personal project for educational purposes.