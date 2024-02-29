# Hangman
It is a text-based Hangman game. The program selects a random word, and the player guesses one letter at a time to uncover the word. You can set a limit on the number of incorrect guesses allowed.

# Execution Procedure
First, we will ask for the name of the user. We will take the user input using the input() method. After execution, the input() method takes the input from the user and returns a string.
Next, we will select a word and ask the user to start guessing the characters in the word.
We will also define the maximum number of attempts the user can take.
Now, we will use a while loop to repeatedly ask the user to guess the character until the attempts are exhausted.
Inside the while loop, if the user guesses the correct character. We will include it in the response. Otherwise, we will notify the user that they made a mistake.
If the user is able to guess all the characters of the word within the maximum number of attempts, they win the game.
If the user exhausts all their attempts before guessing the entire word, they lose
