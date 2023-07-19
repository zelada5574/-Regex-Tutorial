# Regex Tutorial

Hello and welcome to my regex tutorial. By explaining some main concepts, this tutorial should be able to help you better understand and manipulate your code to be as efficient for you as possible.

## Summary

We're going to go over a regular expression to check email addresses. Here's what its gonna look like at the end

    ^([a-zA-Z0-9._%-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,6})*$

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

Regular Expressions are made up of several different components that work together to create the search pattern. These components are called operators and they each have a different function.

### Anchors

Anchors are used to match a position within the string. The caret `^` matches the position before the first character in the string. The dollar sign `$` matches right after the last character in the string.

We use these at the beggining of our expression to make sure that the email address starts with a letter or number and ends with a letter or number.

### Quantifiers

Quantifiers are used to specify how many times a character can repeat itself. The asterisk `*` matches the preceding character zero or more times. The plus sign `+` matches the preceding character one or more times. The question mark `?` matches the preceding character zero or one time. The curly braces `{}` are used to specify the number of times a character can repeat itself. The first number is the minimum number of times the character can repeat itself and the second number is the maximum number of times the character can repeat itself. If there is only one number in the curly braces, then that is the exact number of times the character can repeat itself.

We use these at the end of our expression to make sure that the email address ends with a valid domain name. We also use them in the middle of our expression to make sure that the email address has a valid domain name and a valid email provider with a `+` sign.

### Grouping Constructs

Grouping constructs are used to group subexpressions together. The parentheses `()` are used to group subexpressions together. The vertical bar `|` is used to match either the expression before or after the vertical bar.

We use these to group the whole expression together so that the quantifiers apply to the whole expression and not just the last character.

### Bracket Expressions

Bracket expressions are used to match any one character in a set of characters. The brackets `[]` are used to match any one character in a set of characters. The dash `-` is used to match a range of characters.

We're using the brackets to contain the different sections of the email address and we use the dash inside of the brackets to set a range of characters.

### Character Classes

Character classes are used to match any one character in a set of characters. For example we use /w to match any word character. /d to match any digit character. /s to match any whitespace character. /W to match any non-word character. /D to match any non-digit character. /S to match any non-whitespace character.

### The OR Operator

The OR operator is used to match either the expression before or after the vertical bar. The vertical bar `|` is used to match either the expression before or after the vertical bar.

### Flags

Flags are used to change the way the search pattern is interpreted. The `g` flag is used to perform a global search. The `i` flag is used to perform a case-insensitive search. The `m` flag is used to perform a multiline search.

### Character Escapes

Character escapes are used to escape characters that would otherwise be treated as operators. The backslash `\` is used to escape characters that would otherwise be treated as operators.

## Author

My name is Jaryot Ramirez and I am an aspiring Full Stack Web Developer. You can reach me at jarram999@gmail.com and the link to my github is https://github.com/zelada5574 thank you