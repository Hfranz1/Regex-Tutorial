# Regex-Tutorial

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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
- Mannaging the Analysis Scope
- Capturing Multiple Lines
- Corresponding Tables to information
- Specifying Alternatives
- Evaluating Occurrences
- Specifying Location
- Specifying Fields and Groups
- Matching Character Sets
- Matching Fixed Strings
- Matching Special Characters
### Anchors
Anchors are characters within a regular expression that allow for matching a position before or after characters:

- ```^```-The caret anchor matches the begining text
 - ```$```-The dollar sign anchor matches the end text

 example:
 ```

 ```
### Quantifiers
Indicates the number of characters or expressions to match.

Quantifiers Examples:
- ```*``` - matches a string that is followed by a zero or multiple of the last character
- ```()* ``` - matches a string that has any of the characters followed by zero or more copies of the string that are within the brackets
-  ```?``` - matches a string that is followed by zero or one of the last characters 
-  ```{}``` - matches a string that is followed by as many of the numbers in the brackets of the last character in the string
-  ```+``` - matches a string that is followed by one or more of the last characters 

Example:
```
abc*.        matches a string that had bc followed by zero or more c
a(bc)*       matches a string that had a followed by zero of more copies of cd
abc?         matches a string that had bc followed by zero or one c
abc{5}       matches a string that had bc followed by 5 c
abc+         matches a string that had bc followed by one or more c
abc{5,9}     matches a string that had bc followed by 5 up to 9 c
a(bc){5,9}   matches a string that had a followed by 5 up to 9 of the sequence bc 
```


### Character Classes
Character classes differentiates between types of characters, such as letters and numerical digits.
### The OR Operator

### Flags
Flags are optional parameters that can be added to plain expressions to make it search in different ways. Each flag is followed by a alphabetic character.
 - ```i```  - Insensitive, makes an expression case insensitive
 - ```m```  - Multi-line, when paired with (^$) will match a start and end line, rather than the whole string
 - ```g```  - Global, only returns the first match, after restarting it makes the expression search for all 
### Character Escapes

### Grouping Constructs

### Bracket Expressions

## Author
Hannah Franz

## Links

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
