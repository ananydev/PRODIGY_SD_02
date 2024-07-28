FEATURES :

1. Random Number Generation: The game generates a random number between 1 and 100 each time it starts, providing a new challenge for the player.
2. User Interaction: The game takes input from the user through the console, making it interactive.
3. Attempt Counting: The game keeps track of the number of attempts made by the user, adding a score-like feature to the game.
4. Simple User Interface: The game runs in the console and interacts with the user through simple text prompts, making it easy to understand and play. 



DETAILED BREAKDOWN :

1. Imports:    java.util.Scanner: Used to get input from the user.
               java.util.Random: Used to generate a random number for the user to guess.

2. Main Class and Method:      Class: GuessingGame
                               Main Method: This is where the execution of the program starts.

3. Random Number Generation:    A Random object is created.
                                random.nextInt(100) + 1 generates a random number between 1 and 100 (inclusive).

4. User Interaction:     Scanner object scanner is used to take input from the user.
                         The program prompts the user to guess the number.

5. Game Loop:     A while loop runs until the user guesses the correct number (userGuess != numberToGuess).
                  The user's guess is taken using scanner.nextInt().
                  The number of attempts is incremented with each guess.

6. The program provides feedback:      "Too low. Try again."  if the guess is lower than the number.
                                       "Too high. Try again."  if the guess is higher than the number.

7. End of Game:        The program congratulates the user when the correct number is guessed.
                       The total number of attempts is displayed.
