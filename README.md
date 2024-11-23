# Python Guessing Game 🎮

A simple Python-based guessing game where you try to guess a randomly generated number between 1 and 100. The program provides feedback ("Too high!" or "Too low!") after each guess and keeps track of how many attempts it takes to find the correct number. A great project for beginners to learn Python programming basics!

---

## 🚀 Features
- **Random Number Generation**: The program selects a random number between 1 and 100 using Python's `random` module.
- **User-Friendly Feedback**: Provides hints if the guessed number is too high or too low.
- **Input Validation**: Handles invalid input gracefully using error handling.
- **Attempts Tracking**: Displays the number of attempts taken to guess correctly.

---

## 📋 How to Use

1. **Clone this Repository**:
   ```bash
   git clone https://github.com/your-username/python-guessing-game.git
   cd python-guessing-game
   ```

2. **Run the Script**:
   Ensure Python is installed on your machine. Execute the following command in your terminal:
   ```bash
   python3 guessing_game.py
   ```

3. **Play the Game**:
   - Follow the on-screen prompts.
   - Enter your guesses until you find the correct number.

---

## 💡 Example Gameplay

```plaintext
Welcome to the Guessing Game!
I have selected a number between 1 and 100. Try to guess it.
Enter your guess: 50
Too low! Try again.
Enter your guess: 75
Too high! Try again.
Enter your guess: 62
Congratulations! You guessed the correct number.
It took you 3 attempts to win the game.
```

---

## 📂 Project Structure

```plaintext
├── guessing_game.py  # Main Python script for the game
├── README.md         # Documentation for the repository
```

---

## 🛠️ Skills Demonstrated
- **Random Number Generation** with `random.randint()`
- **Conditional Logic** for comparing guesses
- **Error Handling** using `try-except` blocks
- **Python I/O Operations** for user input and output
