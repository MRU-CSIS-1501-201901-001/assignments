# ColorPool Docs

## Preamble

This is a class you need to make.

Its job in life is to represent a "pool" of colors that a player can use to purchase beast cards.

## Public Methods You Need To Make

### constructor

> You don't need to make one - the default will be fine. (Remember to use appropriate instance variable initializers, though!)
>
> If you **do** decide to make one - and I won't hold it against you if you do - make sure it is a **no-arg constructor**.
>
> A new ColorPool should start off with 0 red, 0 green, and 0 blue colors in it.

### public int numRed()
### public int numGreen()
### public int numBlue()

> These methods return the number of red, green, and blue colors in the pool, respectfully and respectively.
>
> Yes, these are one-liners. Huzzah.

### public void gain(`String`)

> Receives a color String (one of "R", "G", or "B" - case insensitive) and increments the corresponding color in the pool.
>
> If any other String is received, nothing is incremented.

### public void pay(`String`)

> Receives a String of colors (like "RG" or "BBGGRR") and decrements the corresponding colors in the pool.
>
> Counts should never go below 0 - if any incoming String would cause this to happen, the corresponding colors should just go to 0.

### public boolean canPayFor(`BeastCard`)

> Returns true if the current colors in this pool can pay for the incoming card.

### public String toString()

> This is optional; you may find it useful for debugging.