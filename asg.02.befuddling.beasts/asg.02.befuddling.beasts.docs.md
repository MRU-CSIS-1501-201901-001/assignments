# Assignment 02

## Challenge: Befuddling Beasts Game

### Preamble

So when I was coding up the MtG: Arena drill, I was thinking "Hey - this could actually become an assignment!".

So I started to do that, and one thing led to another, and we wound up here. Life's so weird.

If you haven't done the **WEEK-03: MtG card** drill, I'd suggest doing it before continuing. Also, having any of the **WEEK-06: input validation** drills would be useful as well. Oh, and **WEEK-04: rewarder**. But not the hex grid drill - that'd be a jerk move.

#### The Game Of Befuddling Beasts

In Befuddling Beasts (just a name I made up), you have a hand of beast cards that cost a certain combination of colors (Red, Green, and Blue) to play. You also have a "pool" of colors (red, green, and blue) that you use to pay for these beasts.

On your turn, you have 3 options:

- play a beast
- draw a beast **and** a color
- quit the game

Every time you play a creature, your score goes up on a sliding scale:

- beast with cost of 1: 0 points
- beast with cost of 2 or 3: 2 points
- beast with cost of 4 or 5: 7 points
- beast with cost of 6: 10 points

The game is over when you reach 30 points (or you want to quit).

After the game is over, you will be assigned a penalty according to how many cards you have left in your hand:

- 0 cards: no penalty
- 1 card: -5 points
- 2 cards: -14 points
- 3+ cards: -10 points PER CARD

So to get a good score, you have to play beast cards...but you want to try to end the game with as few cards as possible.

---

### What you're going to build

You're going to be making an application that allows a user to play a game of Befuddling Beasts.

Each turn, the user will be shown a display that shows the player what colors they have in their pool, how many points they have, a list of the beasts they have available, and a selection of options.

They will then choose whether they want to play a beast, draw a beast & color, or quit. (There will be some validation going on here. It involves loops. It isn't fun - validation isn't really fun.)

Let's watch a couple of runs so you can get a feel for all this.

**Example Run 1**

![Screenshot](images/capture-01.png)

> Commentary on Run 1
>
> - The application starts up and shows the `PlayAreaView`, which consists of the current colors available (3 red, 4 green, and 3 blue here), the current score (000), a list of beast cards in the player's hand, and some menu options.
> - Although things are all colored nicely, you only need to do that for an A+ level. Maybe you want to wait to do that until later?

**Example Run 2**

![Screenshot](images/capture-02.PNG)

> Commentary on Run 2
>
> - Here we see what happens when a user tries to enter an invalid menu option: a semi-helpful error message is displayed and then the user is re-prompted.

**Example Run 3**

![Screenshot](images/capture-03.PNG)

> Commentary on Run 3
>
> - This is a bit longer...let's walk through this. The player currently is unable to play any cards, thanks to a shortage of R(ed).
> - The first thing we see is that when the player tries to play a card anyway, but since they don't have the colors to do so, they are told "You have no playable card" and the PlayAreaView is displayed again.
> - Next, the player decides to draw, hoping to snag that red. We see that they are told that they've drawn a B(lue) and another beast - notice how the ColorPoolView reflects the addition of the new color, and the HandView displays the new card.
> - The player draws again, this time getting a (R)ed and another card.
> - Now that they have a red, the player chooses P and is asked for the number of the card to play. They bung it up a number of times, so they game keeps prompting them for a valid number until they get it right.
> - After the valid card play, the player is given 7 points (see the `The Game Of Befuddling Beasts` section above for scoring details). This score is shown in the CurrentScoreView.

**Example Run 4**

![Screenshot](images/capture-04.PNG)

> Commentary on Run 4
>
> - Here's a shot of a game ending (here, it's with a quit, but the same could happen if the player reached or surpassed the target ending score of 30 points).
> - The player is given their points for cards scored, a penalty is assigned as described above in the `The Game Of Befuddling Beasts` section, and the final score is presented.
> - Note how the penalty report includes both the penalty points **AND** the number of cards left in hand.
