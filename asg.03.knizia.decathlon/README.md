# Assignment 03

**DUE: Wednesday, April 3, 2019 @ 11:59PM**

**SUBMISSION PROCEDURE**:

To submit your assignment, just use the usual **submit1501** on INS.
When asked for the task identifier, please use **asg03** or **asg3**.

**LATE SUBMISSIONS**

Assignments can be handed in a maximum of 48 hours late. For every 24 hour period, your letter grade will go down by one "level". For example, an A goes to an A-, a B- goes to a C+.

**WEIGHT: 5%**

## DEMONSTRATIONS

Since I have no clue what you're going to build, you will have to demonstrate your application to me. You will need to set up a time with me on **April 4 or 5** to spend 10 minutes where we will sit down together and you will show me your stuff.

## DOCUMENTATION

Again, since you're forging your own path here, I will want some documentation. You will need to use Javadoc-style comments for all public methods in your code **except for the code in the classes I am forcing you to write** (wo Dice, HighScores, etc.).

## A suggested PLAN OF ATTACK

1. Read this document.
1. Familiarize yourself with the rules of the game - you cannot possibly code what you do not understand.
1. Complete the classes I have asked you to complete and get them passing all tests.
1. Use those completed classes - and any others you decide to create yourself - to construct a working application.
1. Profit. Or go mad. Or both.

## A few WARNINGS

- Although the code you need to write isn't necessarily that difficult, this is the first time you've been given free reign on what classes you are actually going to create. This can be a lot of fun - but it can also be challenging.
- You're going to want to test things as you go along; although I will show you in labs how to create your own automated tests, because this is a very interactive game, you'll likely be spending a lot of time running your code, watching it fail, figuring out what's the problem, (hopefully) fixing the problem, and then running it again to see if you actually **did** fix the problem. This is time consuming. Prepare thyself.

## Getting the starting code

You will be adding your own classes to an assignment directory already created for you.

Please copy the directory `/users/library/csis/comp1501/assignments/3.asg.knizia.decathlon` to your home directory.

Any classes you make should be placed, as always, in the `src` directory.

## How to check your work

You have been provided automated tests for the classes I am "forcing" you to make:

- Dice
- DiceCollection
- HighScores
- HighScoresPersistanator
- PlayerScore

As always, you can run tests using the command **make tests** from the `3.knizia.decathlon` directory - don't try and run it from the `src` directory....sucker will NOT work.

If you want to see whether your code is _following the coding standards for this course_, you can run the command **make style -i** from the `3.knizia.decathlon` directory as well.

> There is some overlap between the two tools used to do style checking, so
> you may notice some warnings are repeated between the two tools. If you
> don't understand any of the warnings (they **can** be a little opaque),
> please talk to one of the IAs or your instructor.
