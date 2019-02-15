# MenuValidator Docs

## Preamble

This is a class you need to make.

Its job in life is to validate choices that the user makes at the main menu: that is, it makes sure the user types in one of **P | p | D | d | Q | q**.

## Public Methods You Need To Make

### public MenuValidator(`Scanner`, `String`)

> This is the constructor.
>
> It takes in the Scanner it should be using to get input from the user, and a String representing the letters that are valid for the menu. (For example, in this assignment, the String would be "PDQ".)
>
> You might find it weird to have a Scanner as a parameter....but hopefully not _too_ weird, because you've seen stuff like this before!

### public String validSelection(`String`)

> Takes in a prompt to display to the user, like "Your choice (PDQ)? ".
>
> This method keeps asking the user for a valid letter until such a letter is entered. It then returns that valid letter.
> 
> This method should be case insensitive - BUT it should always return the uppercased version of the valid letter entered.

### public String toString()

> This is optional; you may find it useful for debugging.