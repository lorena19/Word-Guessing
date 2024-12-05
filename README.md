# # Word Guesser Game - README

Welcome to the Word Guesser Game! This Python-based project recreates the classic word-guessing game, challenging players to identify a hidden word one letter at a time within a limited number of attempts. fun way to practice python fundamentals by creating an interactive game!

## Features
- Randomly selects a word from a predefined word bank for an element of surprise 🎲.
- Tracks player guesses and updates the word display dynamically.
- Provides feedback for correct and incorrect guesses.
- Ends the game when the player guesses the word or runs out of attempts.
---

## Getting Started
Follow these steps to set up and run the game in your local environment.

### 1. Clone the Repository
```bash
git clone https://github.com/lorena19/Word-Guessing.git
cd word-guesser-game
```

### 2. Create a Virtual Environment
Using a virtual environment ensures that your Python dependencies are isolated and managed properly.

#### On Windows:
```bash
python -m venv venv
venv\Scripts\activate
```

#### On macOS/Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies
This project doesn't require external libraries, but always good practice to update `pip`:
```bash
pip install --upgrade pip
```

### 4. Run the Game
Start the Word Guesser Game by running:
```bash
python wordgame.py
```

---

## How to Play
1. The game will display the current word with placeholders (`_`) for each letter.
2. Guess one letter at a time by typing it into the terminal.
3. If your guess is correct, the placeholders will be updated with the letter.
4. If your guess is incorrect, you'll lose one attempt.
5. Win the game by guessing all the letters correctly before running out of attempts!

---

## Word Bank
The current word bank includes:
- `rizz`
- `ohio`
- `sigma`
- `tiktok`
- `skibidi`

Feel free to expand the `word_bank` list in the code to include more words!

---

## Additional Notes
This project uses the following Python concepts:
- Random Module: For selecting a random word.
- Lists and Strings: To manage the current state of the word.
- Control Flow: To check guesses and manage game logic.
- Input/Output Handling: For user interaction.

---

## License
Feel free to use and modify this project for learning purposes. Contributions are always welcome!

---

Enjoy the Word Guesser Game and happy coding! 🎉
