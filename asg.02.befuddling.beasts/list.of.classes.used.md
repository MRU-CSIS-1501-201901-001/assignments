# List of Classes Used

Here's a list of all the classes involved in this game. It looks like a lot (and it is, I suppose), but before you hyperventilate, two things:

1. quite a few of the classes are already complete and you don't have to code them up! (But you **will** need to use the public methods from them.)
1. this whole "lots of little classes" thing is very common in object-oriented programming - we want to make classes that do one very specific thing...which makes them actually easy to code, because you can focus on that one thing!

## Completed Classes

These are classes that are fully complete - you can (and should) read them, but you should not alter them in any way. These all hyperlink to the documentation for the class, so click away!

1. [BeastDeck](https://jpratt-mru.github.io/a2.api/BeastDeck.html)
1. [ColorDeck](https://jpratt-mru.github.io/a2.api/ColorDeck.html)
1. [ColorHelper](https://jpratt-mru.github.io/a2.api/ColorHelper.html)
1. [Hand](https://jpratt-mru.github.io/a2.api/Hand.html)
1. [HandView](https://jpratt-mru.github.io/a2.api/HandView.html)
1. [Main](https://jpratt-mru.github.io/a2.api/Main.html)
1. [NumberValidator](https://jpratt-mru.github.io/a2.api/NumberValidator.html)
1. [PlayAreaView](https://jpratt-mru.github.io/a2.api/PlayAreaView.html)

## Partially Completed Classes

These are classes that are _partially_ completed; there are some methods that you will need to complete to make the class work properly:

1. [BefuddlingBeastsGame](class.docs/docs.BefuddlingBeastsGame.md)

## Classes You Must Complete On Your Own

These are classes that you need to create from scratch. **They must follow the public interface given to you**; if they don't, significant mark reduction will occur. I've tried to indicate how easy I think each class is to code (☆ = easiest, ☆☆☆ = hardest). I also the dependencies for the class - that is, what classes you need to complete before you can work on the given class.

These all hyperlink to a document describing the class and what you'll need to code up.

1. [BeastCard](class.docs/docs.BeastCard.md) ☆
   - no dependencies
1. [BetweenValidator](class.docs/docs.BetweenValidator.md) ☆☆
   - no dependencies
1. [ColorPool](class.docs/docs.ColorPool.md) ☆☆½
   - depends on `BeastCard`
1. [ColorPoolView](class.docs/docs.ColorPoolView.md) ☆☆
   - depends on `ColorPool`
1. [CurrentScoreView](class.docs/docs.CurrentScoreView.md) ☆
   - depends on `Scorer`
1. [FinalScoreView](class.docs/docs.FinalScoreView.md) ☆☆
   - depends on `Scorer`
1. [MenuValidator](class.docs/docs.MenuValidator.md) ☆☆
   - no dependencies
1. [Rewarder](class.docs/docs.Rewarder.md) ☆ (assuming you did the drill - otherwise, ☆☆)
   - no dependencies
1. [Scorer](class.docs/docs.Scorer.md) ☆☆☆
   - depends on `Rewarder`
   - depends on `Hand`
