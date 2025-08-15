# Hangman Game 🎯

A simple Python-based command-line **Hangman** game where players guess letters to reveal a hidden word before running out of lives.

---

## 📌 Features
- Random word selection from a predefined list.
- ASCII art stages to show hangman progress.
- Case-insensitive guessing.
- Win/Lose messages at the end of the game.

---

## 📂 Project Structure
- HangmanGame.py # Main game logic
- hangman_words.py # List of words
- hangman_stages.py # ASCII art for hangman stages\

  
---

## 🛠 How It Works
1. A random word is chosen from `hangman_words.py`.
2. The player guesses one letter at a time.
3. Correct guesses reveal the letter(s) in the word.
4. Incorrect guesses reduce lives and progress the hangman drawing.
5. The game ends when:
   - The word is fully guessed (**Win**)
   - Lives reach zero (**Lose**)

---

## ▶️ How to Run
1. Install **Python 3**.
2. Download or clone this repository.
3. Open a terminal in the project folder.
4. Run:
   ```bash
   python HangmanGame.py
    _ _ _ _ _
    Guess a letter: a
    ['_', 'a', '_', '_', '_']
    ...
    You win!
---

##💡 Future Enhancements
- Add difficulty levels.
- Import custom word lists.
- Implement a scoring system.
- Improve ASCII art visuals.

