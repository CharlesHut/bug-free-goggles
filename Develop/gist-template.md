# Title (REgex Email)

Introductory paragraph (Hello my name is charlie and here I will be explaining the different components my regex code snippet.)

## Summary
here I will be explaining how a email Regex works and heres my code snippet `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

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
    the componenets of Regex are Anchors, Quantifiers, Alternation, Syntax and Notation, charecter classes, patterns, Matching, Capturing, Substitution, and Flags
### Anchors
    Anchors match the starting and and ending points so in my code it would be shown in the form of start-^ end-$
### Quantifiers
    Quantifiers allow you to specify how many of a charecter or charecter class should be matched so in my code it is show as the + signs 
### OR Operator
    or operators allow you to match charecters in text strings. in my snippet there is no OR operator but it is usually signified by |
### Character Classes
    charecter classes allow you to define specific sets of charecters that can be used in a search pattern and ini my code snippet is show as the \d
### Flags
    regexes also use flags to modify their behavior these flags allow you to change how the regex behaves such as making it a case insensitive or allowing it to match on multiple lines
### Grouping and Capturing
    Grouping and capturing allow you the match strings of text or sections of it and condence it into groups so you can treat it all as a single unit and this is a example of capturing in my code \da-z\.-
### Bracket Expressions
    bracket expressions are a sting/list of charecters or charecter classes in brackets and in my sting they are show as these[ ]
### Greedy and Lazy Match
    Greedy and lazy match. Greedy will try to match the longest possible sting. and Lazy will try to match the smallest possible string.
### Boundaries
    Boundaries are shown in many different ways such as Anchors for example. Boundaries signify the beginning and ending of a string or of a line of code. 
### Back-references
    Back-references are things that refer to the submatch of a previous cature group and it matches the text in the group and there normaly shown and \N
### Look-ahead and Look-behind
    Lookahead is a expression that asserts and matches whats on the right and Lookbehind is a expression that asserts and matches whats on the left. examples Lookahead = X(?=Y) Lookbehind = (?<=Y)X
## Author
hello My name is Charlie and this is a research page on Regex and here I break down each part of a Regex string and tell you what they do. If you like my work check out my Github page where I have other projects I've worked on. 
