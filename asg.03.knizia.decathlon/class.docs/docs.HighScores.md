# HighScores Docs

## Preamble

This is a class you need to make.

Its job in life is to be a collection of high scores for your game.

(Think of one of [these old-school arcade high score displays](https://www.google.com/search?rlz=1C1GCEV_en&q=arcade+high+score+screen&tbm=isch&source=univ&sa=X&ved=2ahUKEwje1-Cm6OvgAhXTrZ4KHbnjCxkQsAR6BAgFEAE&biw=1920&bih=937).)

## Public Methods You Need To Make

### public HighScores(`int`)

> This is the constructor.
>
> It takes in the maximum number of scores allowed. (So if you make a HighScores object that has a maximum number of scores == 10, only the top 10 player's scores are stored.)

### public boolean isEligible(`PlayerScore`)

> Returns true if the given PlayerScore is greater than 0 AND better than at least the lowest score currently in the collection.
>
> You might find this useful when creating your `add` method....

### public void add(`PlayerScore`)

> Adds the score to the high scores - but only if the score should be there!
>
> **A player scores should only be added if it is greater than 0 AND it's better than at least the lowest score currently there.**

### public PlayerScore ranking(`int`)

> Returns the PlayerScore at the given ranking (which starts at 1). If the ranking given is out of bounds, then returns null...which makes me sad, but there you have it.

### public PlayerScore numScores()

> Returns the number of high scores.