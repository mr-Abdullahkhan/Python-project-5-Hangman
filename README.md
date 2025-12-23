🎯 Hangman Game (Python)
===

This is a classic Hangman game built using Python and played in the command line. The player guesses letters to uncover a hidden word before running out of lives.

---
**📌 Project Description**

The program randomly selects a word from a predefined word list (hangman_words.py).
The player must guess the word one letter at a time. Each incorrect guess reduces lives, and the hangman figure is displayed using ASCII art (hangman_art.py).
The game ends when the player either guesses the word correctly or runs out of lives.

This project helped me practice loops, conditionals, lists, and working with multiple Python files.

---
**🛠️ Technologies Used**

* Python 3
* Command Line / Terminal
* random module
* External Python files:
  * hangman_words.py (word list)
  * hangman_art.py (ASCII art for hangman and logo)
 
---
**▶️ How It Works**

1. A random word is selected from the word list
2. The word is displayed as underscores
3. The player guesses one letter at a time
4. Correct guesses reveal letters in the word
5. Incorrect guesses reduce lives and display a hangman stage
6. The game ends when the word is guessed or all lives are lost

___
**🎮 Example Gameplay**

      Welcome to Hangman!
      Word to guess: _ _ _ _ _
      
      ****************************6/6 LIVES LEFT****************************
      Guess a letter: a
      Word to guess: _ a _ _ _
      ****************************6/6 LIVES LEFT****************************
      Guess a letter: e
      You guessed e, that's not in the word. You lose a life.
      [Displays hangman ASCII stage]

___
**🎯 What I Learned**

1. Using while loops for continuous gameplay
2. Managing game state with variables
3. Tracking correct and incorrect guesses
4. Working with lists and strings
5. Organizing code across multiple files

---
**🚀 Future Improvements**

1. Adding a restart option
2. Preventing invalid or repeated input
3. Showing all guessed letters
4. Adding difficulty levels
5. Enhancing game story and messages

---
**🙌 Acknowledgment**

This project is part of my Python learning journey and helped me understand how to build a complete game using logic, loops, and multiple files.
___
**⭐ Feel free to fork this project or suggest improvements!**
