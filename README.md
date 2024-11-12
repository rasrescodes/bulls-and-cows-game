# Bulls and Cows Game

A Python implementation of the classic "Bulls and Cows" guessing game, where players try to guess a secret 4-digit number with no repeated digits. Each guess provides feedback in terms of "bulls" (correct digits in the correct position) and "cows" (correct digits in the wrong position).

## How to Play

1. **Secret Code Generation**: The game generates a random 4-digit secret number with no repeated digits.
2. **User Input**: The player is prompted to guess the 4-digit number.
3. **Feedback**: For each guess, the game returns:
   - **Bulls**: Number of correct digits in the correct positions.
   - **Cows**: Number of correct digits in incorrect positions.
4. **Win Condition**: The player wins if they guess the number correctly within the given number of tries.

## Code Explanation

- `getDigits(num)`: Converts a number to a list of its digits.
- `noDuplicates(num)`: Checks if a number has no repeated digits.
- `generateNum()`: Generates a 4-digit number with unique digits.
- `numOfBullsCows(num, guess)`: Compares the secret number with the guess and returns bulls and cows counts.

## Sample Run

```plaintext
Enter number of tries: 5
Enter your guess: 1234
1 bulls, 2 cows
Enter your guess: 5678
0 bulls, 1 cows
...
```

## Running the Code

1. Clone the repository or copy the code.
2. Run the script using Python:
   ```bash
   python bulls_and_cows.py
   ```
3. Follow the prompts to play.

## License
This project is open source and available under the MIT License.
