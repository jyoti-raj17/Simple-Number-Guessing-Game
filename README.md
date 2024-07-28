# Simple-Number-Guessing-Game
A number guessing game where the program randomly selects a number within a range, and the user has to guess it. The program also provide feedback (too high, too low) and count the number of attempts.


Step-by-step algorithm:

1. Ask User to input the lower bound and upper bound of the range.
2. The compiler generates a random integer between the range and store it in a variable for future references.
3. For repetitive guessing, a while loop will be initialized.
4. If the user guessed a number which is greater than a randomly selected number, the user gets an output “Try Again! You guessed too high“
5. Else If the user guessed a number which is smaller than a randomly selected number, the user gets an output “Try Again! You guessed too small”
6. And if the user guessed in a minimum number of guesses, the user gets a “Congratulations! ” Output.
7. Else if the user didn’t guess the integer in the minimum number of guesses, he/she will get “Better Luck Next Time!” output.

