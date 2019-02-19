# Assignment 02

**DUE: Friday, March 8, 2019 @ 11:59PM**

**SUBMISSION PROCEDURE**:

To submit your assignment, please use the usual **submit1501** on INS.

When asked for the task identifier, please use **asg02**.

**WEIGHT: 5%**

## A suggested PLAN OF ATTACK

1. read all of this document
1. read [asg.02.befuddling.beasts.docs.md](asg.02.befuddling.beasts.docs.md); it tells you what this assignment is about and shows you how the software you are going to build looks and behaves
1. look at the [list of classes used](list.of.classes.used.md) - it will give you a great idea at which classes you need to work on and which ones have been done for you; it also gives an estimate on how hard each class you need to code is
1. take a **quick** glance through the docs for the different classes that are involved in the software you are building - they'll give you a feel for how all the pieces of the application work together
1. cherry pick a non-threatening class from the list of classes used and get it passing its tests. Don't forget to run both `make tests` and `make style` periodically to maintain sanity.
   - look at the **How to check your work** section below on how to run the different types of tests
1. once all tests are passing green and you've completed the private helper methods in `BefuddlingBeastsGame.java`, you should have a working application.

## A few WARNINGS, or perhaps HINTS

- The number of classes you are being asked to build might seem overwhelming - perhaps even disheartening. As with many things in life that seem this way at first glance, the toughest part is taking that first step. Once you get moving, you'll start to build momentum.
- Don't forget to run tests and style checks frequently; it's **SOOOO** much easier to do lots of tiny little fixes as you work than one monster fix at the end.
- Don't forget to take a look at the tests as you're working; as mentioned in [lab.11](https://github.com/MRU-CSIS-1501-201901-001/labs/blob/master/lab.11.md), they provide valuable information and aren't that hard to read.

## Getting the starting code

You will be adding your own classes to an assignment directory already created for you.

Please copy the directory `/users/library/csis/comp1501/assignments/2.asg.befuddling.beasts` to your home directory.

Any classes you make should be placed, as always, in the `src` directory.

## How to check your work

If you want to check whether your code is _behaving as expected_, you can run the command **make tests** from the `2.asg.befuddling.beasts` directory - don't try and run it from the `src` directory....sucker will NOT work.

> You can now run tests for an individual class (instead of all of them at once). To do so, just run `make [class name all lowercase]`. For example:
>
> - **make beastcard**
> - **make currentscoreview**
> - **make menuvalidator**

If you want to see whether your code is _following the coding standards for this course_, you can run the command **make style -i** from the `2.asg.befuddling.beasts` directory as well.

> There is some overlap between the two tools used to do style checking, so
> you may notice some warnings are repeated between the two tools. If you
> don't understand any of the warnings (they **can** be a little opaque),
> please talk to one of the IAs or your instructor.
