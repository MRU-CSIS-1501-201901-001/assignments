# Scorer Docs

## Preamble

This is a class you need to make.

Its job in life is to handle all the logic associated with scoring during the game; that is, determining; 

- how many points you get for scoring a given beast card (based on its cost)
- how many points you lose for having cards left in hand at the end of the game
- when a game is over

This is (IMO) the hardest of the classes to code up. I could be wrong, though.

## Public Methods You Need To Make

### instance variables

This might not be apparent at first glance, so I'll provide some hints to help you figure out what instance variables are needed here:

- in order to figure out how many cards the player has in their Hand (which is needed to figure out penalty points, right?), you need to have a Hand!
- in order to figure out how many points to award for a given BeastCard play, you need to have an object that knows how to award points...
- in order to figure out how many points to penalize at the end of the game, you need to have another object that knows how to award points (negative points, in this case)...
- in order to keep track of how many points the player has currently scored from playing cards, you'll need something to do that
- in order to figure out whether the game is over, you'll need something to keep track of the score that triggers the end of the game...

### public Scorer(`int`, `Hand`)

> This is the constructor. 
>
> It takes in the score at which the game should end and the Hand of the user.
>
> It needs the former to decide whether the game is over and the latter to figure out penalty points at the end of the game.

### public void updateScore(`BeastCard`)

> This method updates the player's current score based on the incoming cards cost.

### public int scoreFromCardsPlayed()

> This method returns the number of points the player has currently scored from playing beast cards.

### public int numCardsLeft()

> This method returns the number of cards left in the player's Hand.

### public int penaltyForCardsLeft()

> This method returns the size of the penalty awarded to the player at the end of the game.

### public boolean gameEndingScoreReached()

> This method returns true if the current score from cards played has met or exceeded the score that triggers the end of the game.


### public String toString()

> This is optional; you may find it useful for debugging.
