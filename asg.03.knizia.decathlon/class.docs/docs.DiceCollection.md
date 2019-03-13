# DiceCollection Docs

## Preamble

This is a class you need to make.

Its job in life is to represent a _group_ of one or more dice. (You may notice that many of the events in the game involve throwing **groups** of dice, so this class will see a lot of use!) You will need to complete the Dice class before doing this one.

## Public Methods You Need To Make

### public DiceCollection(`ArrayList<Dice>`)

> This is the constructor.
>
> It takes in an ArrayList of the Dice objects that are in this DiceCollection.

### public int total()

> Returns the sum of all dice in this DiceCollection.
>
> If **any** of the dice in this collection have a -1 value, then this method should return -1.

### public void roll()

> Rolls **all** the dice in this collection.

### public ArrayList<Integer> values()

> Returns the numbers currently showing on the dice in this collection. Some of them may be -1.

### public boolean contains(`int`)

> Returns true if the given integer can be found in any dice in this collection.