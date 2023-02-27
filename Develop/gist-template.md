# (Regular Expression)

JavaScript has many useful methods that can check if a string contains a certain letter or phrase

## Summary

Regular expressions, or regex for short, are a series of special characters that define a search pattern.

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

### Anchors
The characters ^ and $ are both considered to be anchors.
The ^ anchor signifies a string that begins with the characters that follow it. This could be in one of two formats

### Quantifiers
Quantifiers set the limits of the string that your regex matches (or an individual section of the string). They frequently include the minimum and maximum number of characters that your regex is looking for

### Grouping Constructs
The “Matching a Username” regex is fairly straightforward and open-ended about what it accepts. As regular expressions grow more complicated, you may check multiple parts of a string to determine that different sections fulfill different requirements. To break these sections up, you'll need to use grouping constructs

### Bracket Expressions

### Character Classes
A character class in a regex defines a set of characters, any one of which can occur in an input string to fulfill a match. We've actually already discussed some character classes. The bracket expressions outlined previously, including positive and negative character groups, are considered character classes

### The OR Operator
Remember that a bracket expression does not require the string to meet all of the requirements in the pattern. This means that [a-z0-9_-] searches for alphanumeric characters or the two special characters included in the pattern. Often, you'll want to add this same logic outside of a bracket expression, especially within a grouping construct or between two different grouping constructs.

### Flags
We started this tutorial by explaining that as a literal, a regex must be wrapped in slash characters. The one exception to this rule is with the component known as flags. Flags are placed at the end of a regex, after the second slash, and they define additional functionality or limits for the regex. There are six optional flags that can be used, either separately or together and in any order, but these are the three you're most likely to encounter

### Character Escapes
The backslash (\) in a regex escapes a character that otherwise would be interpreted literally

## Author

Recent UCLA Bootcamp student, that has a passion for using the benefits of technology to help man kind. Eagerly seeking new challenges that utilize my acquired skills. 
3P https://github.com/ilike3p
