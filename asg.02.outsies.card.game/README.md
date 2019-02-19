# Assignment 01

**DUE: Friday, February 15, 2019 @ 11:59PM**

**SUBMISSION PROCEDURE**:

To submit your assignment, just use the usual **submit1501** on INS.
When asked for the task identifier, please use **asg01**.

**WEIGHT: 5%**

## A suggested PLAN OF ATTACK

1. read all of this Readme
1. read [asg.01.judo.scoring.docs.md](asg.01.judo.scoring.docs.md); it tells you what this assignment is about and shows you how the software you are going to build looks and behaves
   - **don't** skip the video about the scoring rules of judo - if you don't know how the sport is scored, you cannot possibly do this assignment!
1. take a **quick** glance through the docs for the 5 different classes that are involved in the software you are building - they'll give you a feel for how all the pieces of the application work together
1. start by coding the required public methods for `JudoMatch`; use the tests provided to let you know if things are working correctly **AND** make sure you run the style tests as well as you go - it's MUCH easier to fix things as you go along than have a big, depressing wad of warnings to wade through at the end
   - look at the `How to check your work` section below on how to run the different types of tests
1. once all the tests for `JudoMatch` are running green, you can then start working on `JudoScoreboard`; again, use the tests provided to let you know if things are working correctly
1. that's it - once both classes are passing all the tests, the application should be working!

## A few WARNINGS

- For most of you, this is your first programming assignment. Programming assignments will _always_ take longer than you think. Because you **will** get stuck in places, if you try and do this assignment a day or two before it's due, your life will be a grey and dismal place.

- You might be dismayed at the amount of text in the instructions. It's there for a reason. Skim at your peril.
  - Your instructor reserves the right to peevishly say, "It's in the docs." when asked any question whose answer is in the docs.

## Getting the starting code

You will be adding your own classes to an assignment directory already created for you.

Please copy the directory `/users/library/csis/comp1501/assignments/1.asg.judo.scoring` to your home directory.

Any classes you make should be placed, as always, in the `src` directory.

## How to check your work

If you want to check whether your code is _behaving as expected_, you can run the command **make tests** from the `1.asg.judo.scoring` directory - don't try and run it from the `src` directory....sucker will NOT work.

If you want to see whether your code is _following the coding standards for this course_, you can run the command **make style -i** from the `1.asg.judo.scoring` directory as well.

> There is some overlap between the two tools used to do style checking, so
> you may notice some warnings are repeated between the two tools. If you
> don't understand any of the warnings (they **can** be a little opaque),
> please talk to one of the IAs or your instructor.
