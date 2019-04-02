# Dice Docs

## Preamble

This is a class you need to make.

Its job in life is to represent a single six-sided dice. (I know that technically, it should be called "die", but c'mon.)

Your dice has to behave in two different ways, depending on which of its 2 constructors is called:

- if you call the constructor with a String, then the new dice will use the String's contents to determine what numbers that dice will roll. 
  > So, for example, if you made a dice like this:
  >
  > `new Dice("1 3 2")` 
  >
  > then the first time this dice is rolled, it would come up a 1; the second time rolled, it would come up a 3; the third time, a 2; any rolls after that would come up -1.
- if you call the no-arg constructor, then the new dice will behave like a normal "fair" dice, rolling a number between 1 to 6 with equal probability
  > You will want to do a little reading up on using Java's `Random` class to figure out how to do this.

### Why even bother with 2 constructors?!?

Good question. It's because of testing - it's a right pain to test something that involves randomness. By creating a dice that behaves predictably, both **my** tests (and hopefully **your** tests) have a _much_ easier time of things.

## Public Methods You Need To Make

### public Dice(`String`)

> This is one of the constructors.
>
> The parameter is a String (let's call it the "preset String") containing space-separated integers.
>
> If there are any non-integers in the String, the dice will behave as described below in `value()`.

### public Dice()

> This is the other constructor, used to make a normal "fair" dice.

### public int value()

> This returns the current value of the dice (usually between 1 and 6).
>
> If the dice hasn't been rolled yet, or if the next value in the String used to initialize the dice isn't a valid integer, this method returns -1.

### public void roll()

> Rolls this dice, either generating a new random number, or setting the next value to be the next integer value in the preset String.
>
> If there are no more numbers in the preset String, the next value should be -1.
