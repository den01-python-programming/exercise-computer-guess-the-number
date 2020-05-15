# Exercise - Computer guess the number

Implement a program in Python which guesses a random number that the computer has chosen.

**Notes: In order for the tests to pass you will have to follow the guidelines below:**

- Use the string `"I guessed " + str(guess) + "."` when outputting the user's guess.
- Input the string `You got it right!` when the answer is right.
- Input the string `Too high!` when the guess is too high.
- Input the string `Too low!` when the guess is too low.

You might find the following helpful:

```plaintext
user thinks of random number (no coding here!)

loop until the computer gets it right
    computer guesses random number

    if the guess is right
        user inputs yes
    otherwise
        if the number is too low
            user inputs higher
        if the number is too high
            user inputs lower
```

Implement the program so that the following issues are fixed:

- Tell the computer what *higher* and *lower* means.
- Don't let the computer guess the same answer twice.
