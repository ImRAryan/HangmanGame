# Hangman Game in Java

A simple **console-based Hangman game built in Java** where players guess the name of a car letter by letter. The program randomly selects a word from a text file and the player must guess the correct letters before the hangman drawing is completed.

---

## Features

- Random word selection from an external **text file**
- Console-based **interactive gameplay**
- Visual **ASCII Hangman drawing** for wrong guesses
- Tracks correct and incorrect guesses
- Game ends when the player guesses the word or reaches the maximum number of wrong guesses

---

## Technologies Used

- **Java**
- **File Handling** (`BufferedReader`, `FileReader`)
- **Collections Framework** (`ArrayList`)
- **Random Class**
- **Scanner for User Input**

---

## How the Game Works

1. The program loads a list of **car names** from `words.txt`.
2. A random word is selected as the hidden word.
3. The player guesses one letter at a time.
4. If the guess is correct, the letter appears in the word.
5. If the guess is wrong, a part of the **hangman figure** is drawn.
6. The game ends when:
   - The player guesses the entire word (**You Win**), or
   - The hangman drawing is completed (**Game Over**).
