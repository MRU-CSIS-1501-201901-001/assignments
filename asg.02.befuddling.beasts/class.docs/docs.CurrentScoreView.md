# CurrentScoreView Docs

## Preamble

This is a class you need to make.

Its job in life is to return a String with a specific format that can be placed in the [PlayAreaView](https://jpratt-mru.github.io/a2.api/PlayAreaView.html).

## Public Methods You Need To Make

### public CurrentScoreView(`Scorer`)

> This is the constructor. 
>
> It has one `Scorer` parameter. It uses this to figure out how many points have been earned from playing beast cards, so that it can display that information properly.

### public String view()

> This method returns a specifically-formatted String - take a look at the sample runs in [the main docs](https://github.com/MRU-CSIS-1501-201901-001/assignments/blob/master/asg.02.befuddling.beasts/asg.02.befuddling.beasts.docs.md) to see what it should look like. (Note the number of leading 0s....)

### public String toString()

> This is optional; you may find it useful for debugging.
