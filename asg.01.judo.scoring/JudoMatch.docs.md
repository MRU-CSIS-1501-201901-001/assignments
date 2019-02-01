# JudoMatch Docs

## Preamble

This is a class you need to make. Its job in life is to create the scoreboard that you see in the sample runs.

This class has quite a few public methods you need to make, but most of them are small (like 1 line).

## Public Methods You Need To Make

### public JudoMatch(`int`)

> This is the constructor.
>
> It has one int parameter - the amount of time, in seconds, the given match is supposed to last.

###  public void process(`String`)

> This method takes in an event String and changes the match's state accordingly.

### public boolean over()

> This method returns true if the match is over.

### public boolean wonByIppon()

> This method returns true if an athlete has scored an ippon.

### public boolean wonByAwasete()

> This method returns true if an athlete has scored two waza-ari.

### public String winner()

> Returns "white" if the match has a winner and the winner is white.
>
> Returns "blue" if the match has a winner and the winner is blue.
>
> Return "tie" if the match has no winner.

### public int timeRemaining()

> Returns the number of integers remaining in the match.

### public int numIpponWhite()
### public int numIpponBlue()
### public int numWazaAriWhite()
### public int numWazaAriBlue()
### public int numYukoWhite()
### public int numYukoBlue()

> Each of these methods return the number of X the athlete of color Y has.