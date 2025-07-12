# Flappy Bird Game

A simple Flappy Bird game built with HTML5 Canvas and JavaScript.

## Description

This project is a basic implementation of the classic Flappy Bird game. The player controls a bird that must navigate through a series of pipes by flapping to avoid collisions. The score increases as the bird passes each pipe. The game ends if the bird hits a pipe or the ground/ceiling. Press the spacebar to flap, and press 'R' to restart after a game over.

## Getting Started

### Prerequisites
- A modern web browser (e.g., Chrome, Firefox, Edge)
- A text editor (e.g., VS Code) for modifying the code
- Git installed to clone the repository

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/flappy-bird-game.git
   ```
2. Navigate to the project directory:
   ```bash
   cd flappy-bird-game
   ```
3. Open `index.html` in a web browser to play the game.

Alternatively, you can serve the project using a local server:
- Using Python:
  ```bash
  python -m http.server 8000
  ```
  Then open `http://localhost:8000` in your browser.

## How to Play
- **Flap**: Press the **Spacebar** to make the bird flap and rise.
- **Avoid**: Navigate through the gaps between the green pipes.
- **Score**: Earn points by passing through each pipe.
- **Game Over**: The game ends if the bird hits a pipe or goes out of bounds.
- **Restart**: Press **R** to restart the game after a game over.

## File Structure
- `index.html`: The main game file containing HTML, CSS, and JavaScript.
- `README.md`: This file, providing project information.
- `.gitignore`: Ignores unnecessary files (e.g., `node_modules`, `.DS_Store`).

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Inspired by the original Flappy Bird game by Dong Nguyen.
- Built with vanilla JavaScript and HTML5 Canvas.