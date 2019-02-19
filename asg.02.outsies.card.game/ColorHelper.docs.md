# ColorHelper Docs

## Preamble

This class contains methods that will help you create colored Strings.

You can use `ColorHelper.coloredString` in `JudoScoreboard` to make the text in the blue athlete's row blue. (You don't **have** to do this - but it **is** required for an A+.)

## Public Methods

### static String coloredString(String colorName, String s)
> <pre>
> /**
>  * Returns a string that will print in color in a terminal that
>  * can display ANSI colors.
>  *
>  * For example, ColorHelper.coloredString("green", "foo") returns a
>  * green "foo".
>  *
>  * Recognized colors (case insensitive) are:
>  *
>  * "BLACK"
>  * "RED"
>  * "GREEN"
>  * "YELLOW"
>  * "BLUE"
>  * "PURPLE"
>  * "CYAN"
>  * "WHITE"
>  * "GRAY"
>  * "LIGHTBLUE"
>  * "PINK"
>  *
>  * If an unknown color string is passed, WHITE is applied.
>  */
> </pre>