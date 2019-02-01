# JudoScoreboard Docs

## Preamble

This is a class you need to make. Its job in life is to create the scoreboard that you see in the sample runs.

## Public Methods You Need To Make

### public JudoScoreboard(`JudoMatch`)

> This is the constructor. 
>
> It has one `JudoMatch` parameter - it needs this because the match "knows" much of what that the scoreboard needs to display: the current scores for each athlete and the time remaining in the match.

### public String display()

> This method returns a String that is everything that you see between the `=========` lines in the sample output.
>
> You will likely want to use helper methods for this method - if you don't things are going to be _fuuuuugly_!
