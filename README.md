# Plank Puzzles

A brain-challenging puzzle game where players need to arrange wooden planks with bolts to solve each level. The game features 99 increasingly difficult levels with a time constraint of 59 seconds per level.

## Features

- 99 challenging levels
- Timer-based gameplay
- Intuitive drag-and-drop interface
- Hint system
- Level progression system
- Mobile-friendly design

## How to Play

1. Click on a plank to select it
2. Click on another plank to swap their positions
3. Arrange the planks to match the target pattern
4. Complete the level within 59 seconds
5. Use hints if you get stuck
6. Progress through all 99 levels

## Technical Details

The game is built using:
- HTML5
- CSS3
- JavaScript

## Installation

1. Clone this repository
2. Open `index.html` in a web browser
3. Start playing!

## Development

To add new levels, modify the `levels.js` file following the existing level format:

```javascript
{
    width: 3, // Width of the game board
    planks: [
        { bolts: 2 }, // Number of bolts on each plank
        { bolts: 3 },
        // ... more planks
    ]
}
```
