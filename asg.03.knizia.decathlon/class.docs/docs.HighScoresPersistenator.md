# HighScoresPersistenator Docs

## Preamble

This is a class you need to make. My apologies for the name - I was in a whimsical mood when I was coding it up.

Its job in life is to handle the loading and saving of HighScores into a file.

The file must be as follows: 0 or more lines that have this format:

> [initials][whitespace][score]

The rows must be in descending score order (so the highest score is on the top, with lower scores following after).

Here's an example:

~~~ text
JZA 29
ARP 29
FOO 18
GUF 5
~~~

## Assumptions You Can Make

- When you read scores in from a text file, the file will be well-formed; that is, there will be no errors in the format that might screw up your code.

### Why not put this behaviour in HighScores instead?

Good question. It's all about wanting to have a class be very focussed in what it's trying to do. (This is what the [Single Responsibility Principle](https://en.wikipedia.org/wiki/Single_responsibility_principle) is all about.)

The `HighScores` class should only be concerned with its primary jobs: being a collection of high scores and making sure that new ones are placed in the right spot; deciding what format files should be and handling all the file exceptions and such deserves its own class.

## Public Methods You Need To Make

### public HighScoresPersistenator(`int`, `String`)

> This is the constructor.
>
> It takes in the size of HighScores object to use when loading/saving and the name of the file to load/save from.

### public HighScores load()

> Creates a HighScores object of the size given in the constructor and populates it using the data from the file with the name given in the constructor.
>
> If the file cannot be found, this method should throw a **FileNotFoundException**.

### public void save(`HighScores`)

> Saves the contents of the given HighScores object into the file with the name given in the constructor.
>
> If the file cannot be found, this method should throw a **FileNotFoundException**.
