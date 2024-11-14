# Hangman-Game-in-C
Hangman game is a popular and simple game in which the player has to guess the word based on the given hint. In this article, we will write a program for the hangman game using C programming language.

# What is the Hangman Game?
Hangman is a word puzzle game that involves:

A secret word: A word is selected and its number of characters is displayed to the user. The player then has to guess each letter of the word.

Limited attempts: The guessing player has a fixed number of tries (usually six) to guess the word.

Display: The game displays the partially guessed word with blanks for unguessed letters.

Winning/Losing: The guessing player wins if they think is the word within the allowed attempts; otherwise, they lose.

There is a graphical representation of a person who keeps getting closer to hanging whenever a wrong guess is made hence the name “Hangman”

# Hangman game in c
 

The game challenges players’ word-guessing skills and deductive reasoning.

Logic Behind the Game
The logic of the Hangman program is to take a secret word and guess it letter by letter.
The player has a limited number of wrong guesses before they lose the game.
If the player guesses all of the letters in the word correctly before running out of guesses, they win the game.

The program works by keeping track of the following information:

The secret word
The letters that have been guessed
The number of wrong guesses
In each iteration of the game loop, the program displays the current state of the guessed word and asks the player to guess a letter. 
The program then checks if the guessed letter has already been guessed.
If it has, the program prompts the player to guess again. If the guessed letter has not already been guessed, the program checks if it is in the secret word. 
If it is, the program updates the guessed word to include the letter. 
If the guessed letter is not in the secret word, the program increments the number of wrong guesses.

The game loop continues until the player either guesses the secret word correctly or runs out of guesses. If the player guesses the secret word correctly, the program displays a message congratulating them and the game ends. If the player runs out of guesses, the program displays a message revealing the secret word and the game ends.
