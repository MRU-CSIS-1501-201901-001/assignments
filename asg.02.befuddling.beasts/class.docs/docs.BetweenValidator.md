# BetweenValidator Docs

## Preamble

This is a class you need to make.

If you've done the `WEEK-06: between validator (non-static)` drill, congratulations - you're basically done! If not, congratulations - you can use the code you write here to complete that drill. Win-win, baby.

This class' job in life is to let you know whether a given number is between two other numbers. The lower and upper bounds are inclusive.

## Public Methods You Need To Make

### public BetweenValidator(`Scanner`, `int`, `int`)

> This is the constructor.
>
> It takes in the Scanner it should be using to get input from the user, an integer representing a lower bound, and an integer representing an upper bound.
>
> You might find it weird to have a Scanner as a parameter....but hopefully not _too_ weird, because you've seen stuff like this before!

### public int validInclusiveNumber(`String`)

> Takes in a prompt to display to the user, like "Please enter a number between 1 and 5:".
>
> This method keeps asking the user for a number between the lower and upper bound until such a number is entered. It then returns that valid number.

### public String toString()

> This is optional; you may find it useful for debugging.