# 3D Tetris Game

A modern implementation of the classic Tetris game built with Three.js, featuring 3D graphics and enhanced gameplay mechanics.

## Features

- 3D graphics with dynamic lighting and shadows
- Multiple difficulty levels (Easy, Normal, Hard)
- Progressive difficulty scaling
- Score tracking and level progression
- Game pause functionality
- Responsive design
- Game over screen with restart option

## Getting Started

### Prerequisites

No special prerequisites are needed. The game runs in any modern web browser.

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/3d-tetris.git
```

2. Navigate to the project directory:
```bash
cd 3d-tetris
```

3. Open `index.html` in your web browser.

That's it! No build process or dependencies to install.

## How to Play

### Controls

- **Left Arrow**: Move piece left
- **Right Arrow**: Move piece right
- **Down Arrow**: Move piece down faster
- **Up Arrow**: Rotate piece
- **P**: Pause game

### Scoring System

- Single line clear: 100 points
- Score multipliers based on difficulty:
  - Easy: 0.8x
  - Normal: 1.0x
  - Hard: 1.2x

### Difficulty Levels

- **Easy**: Slower piece descent, higher score threshold for level-ups
- **Normal**: Balanced gameplay
- **Hard**: Faster piece descent, lower score threshold for level-ups

## Technical Details

### Technologies Used

- HTML5
- JavaScript
- Three.js for 3D rendering
- CSS3 for UI styling

### Code Structure

The game consists of three main components:

1. **Game Logic**: Handles piece movement, collision detection, and scoring
2. **3D Rendering**: Manages the Three.js scene, camera, and rendering
3. **UI Layer**: Controls game overlays, menus, and user input

### Performance Considerations

- Optimized render loop
- Efficient collision detection
- Minimal DOM updates
- Responsive design considerations

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Future Enhancements

- [ ] Add multiplayer support
- [ ] Implement high score leaderboard
- [ ] Add sound effects and background music
- [ ] Create more piece variations
- [ ] Add touch controls for mobile devices

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Original Tetris game concept by Alexey Pajitnov
- Three.js documentation and community
- Contributors and testers
