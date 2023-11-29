# Regex Tutorial

In this guide we will disect the common expression listed under summary which is commonly used for validating email addresses in various programming contexts.

## Summary

We will go over the Regex for matching an email:

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

We will be breaking down each part of this regex and explain its function.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors

In the regex provided the '^' at the beginning and the '$' at the end are anchors. 

### Quantifiers

The quantifier ensure that there is at least one valid character before the at '@' symbol.

### OR Operator

The OR operater is not present in this regex. But to define what an or operator is or what it looks like, it is the vertical '|' symbol. 

### Character Classes

Character classes also known as square brackets '[]', define a set of characters from which the regex engine can match one character. It groups classes together.

### Flags

Flags are not being used in the regex provided. Flags can modify the or change how a regex expression behaves, an example of a flag is 'i'for case-insensitivity. 

### Grouping and Capturing

Grouping in regex is represented by the parentheses '()'. Its two purposes in the regex is to groups components together and it captures the matched message. 

### Bracket Expressions

Bracket expressions are used to specify the range pf characters allowed. The expression [a-z\.] matches any lowercase letter or a dot.

### Greedy and Lazy Match

In the regex provided the quantifier + is greedy because its ensuring maximal matching. If one would want to make them lazy they would use the question '?' sign.

### Boundaries

Boundaries in regex, such as ^ and $ in the regex provided, define the limits within which the pattern should match. ^ represents the start of a line, and $ represents the end.

### Back-references

 In the provided regex expression there are no back-references. Back references allow you to reuse a matched group within the same regex. They are represented by \1,.

### Look-ahead and Look-behind

Look-ahead and Look-behind are not used in the provided regex expression. Look-ahead (?=...) and look-behind ((?<=...)) assertions are used to ensure that a certain pattern is (or is not) followed by another pattern without including it in the match. 

## Author

My name is Roniece Garrison and I wrote this tutorial as a homework for my Web Development bootcamp. Explore more of my projects on my [Github-Profile](https://github.com/Ronithenewcoder/regex-tutorial)
