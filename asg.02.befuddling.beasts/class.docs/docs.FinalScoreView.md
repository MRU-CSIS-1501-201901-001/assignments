# FinalScoreView Docs

## Preamble

This is a class you need to make.

Its job in life is to return a String with a specific format that can be placed in the [PlayAreaView](https://jpratt-mru.github.io/a2.api/PlayAreaView.html).

## Public Methods You Need To Make

### public FinalScoreView(`Scorer`)

> This is the constructor. 
>
> It has one `Scorer` parameter. It uses this to figure out the points from cards played, how many cards were left in hand, what the penalty was for cards left in hand, and the final score, so that it can display that information properly.

### public String view()

> This method returns a specifically-formatted String - take a look at the sample runs in [asg.02.befuddling.beasts.docs](asg.02.befuddling.beasts.docs.md) to see what it should look like. (Note the number of leading 0s....)

### public String toString()

> This is optional; you may find it useful for debugging.
