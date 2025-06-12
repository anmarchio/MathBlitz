# MathBlitz (Vibe Coded)
MathBlitz is a single-player web-based game designed to test and improve your mental math skills. The game presents random arithmetic problems (addition, subtraction, multiplication, or division) with increasing difficulty as you progress. Players must solve as many problems as possible within a 60-second time limit to achieve a high score.

## Features
- **Randomized Math Problems**: Generates addition, subtraction, multiplication, or division problems with numbers scaled by difficulty level.
- **Progressive Difficulty**: The difficulty increases every 5 correct answers, making numbers larger and problems more challenging.
- **Timed Gameplay**: Players have 60 seconds to solve as many problems as possible.
- **Scoring System**: Earn 10 points per correct answer, with a bonus for remaining time when achieving 25 correct answers.
- **Responsive UI**: Simple, intuitive interface with start, submit, and restart functionality.
- **Local Storage**: Saves the player's high score in the browser's local storage for persistence across sessions.

## How to Play
1. Click the "Start" button to begin the game.
2. A math problem (e.g., `5 + 3 = ?`) will appear.
3. Enter your answer in the provided input field and click "Submit" or press Enter.
4. If correct, a new problem appears, and your score increases by 10 points.
5. If incorrect, the answer field is cleared for another attempt.
6. The game ends when the 60-second timer runs out or you solve 25 problems correctly.
7. Your final score, including any time bonus (5 points per second remaining for 25 correct answers), is displayed.
8. Click "Restart" to play again. Your high score is saved and displayed.

## Installation
Since MathBlitz is a web-based game, no installation is required. You can run it directly in a web browser.

### Running Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/anmarchio/MathBlitz.git
   ```
2. Navigate to the repository folder:
   ```bash
   cd MathBlitz
   ```
3. Open `mathblitz.html` in a modern web browser (e.g., Chrome, Firefox, Edge) by double-clicking the file or serving it via a local server.

### Running via a Local Server (Optional)
For a better development experience or to avoid CORS issues:
1. Install a simple HTTP server, such as `http-server` via npm:
   ```bash
   npm install -g http-server
   ```
2. Run the server in the repository folder:
   ```bash
   http-server
   ```
3. Open your browser and navigate to `http://localhost:8080/mathblitz.html`.

## Technologies Used
- **HTML5**: Structure of the game interface.
- **CSS3**: Styling for a clean and centered layout.
- **JavaScript**: Game logic, including problem generation, timer, scoring, and local storage.

## File Structure
- `mathblitz.html`: The main (and only) file containing the HTML, CSS, and JavaScript code for the game.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request with a description of your changes.

## Known Issues
- Division problems may occasionally result in non-integer answers due to the random number generation. The game expects exact integer inputs, which may confuse players.
- The UI could be enhanced for better accessibility (e.g., ARIA labels, keyboard navigation).
- No pause functionality is available during gameplay.

## Future Improvements
- Add difficulty settings (e.g., easy, medium, hard).
- Support for decimal or fraction-based answers in division problems.
- Enhance accessibility with ARIA attributes and better keyboard support.
- Add sound effects or animations for a more engaging experience.
- Include a pause button to allow breaks during gameplay.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Created by [anmarchio](https://github.com/anmarchio).
- Inspired by classic mental math games to promote quick thinking and arithmetic skills.
