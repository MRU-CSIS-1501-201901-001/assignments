# PlayerScore Docs

## Preamble

This is a class you need to make. It's insanely easy.

Its job in life is to represent a single player's score for a game of Decathlon. A PlayerScore object is just the player's 3 initials (we'll assume that all players just use 3 initials) and the numerical value of the score. (Think of one row of [these old-timey arcade high score displays](https://www.google.com/search?rlz=1C1GCEV_en&q=arcade+high+score+screen&tbm=isch&source=univ&sa=X&ved=2ahUKEwje1-Cm6OvgAhXTrZ4KHbnjCxkQsAR6BAgFEAE&biw=1920&bih=937).)

## Public Methods You Need To Make

### public PlayerScore(`String`, `int`)

> This is the constructor.
>
> It takes in the initials of the player and their score.

### public int score()

> Returns the value of the player's score.

### public String initials()

> Returns the initials of the player.