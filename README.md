# Regex-Tutorial
This is a guid to Regex, through this we will be looking into how these expressions work. While regex can seem overwhelming, just like with any programming, it can be broken down into smaller easier to understand parts.

## Summary

Regex is a string of text that allows a user to create seach for patterns that match, locate text, and manage.
<p>
Example: expression used to match e-mails
 </p>
 
```
/[\w._%+-]+@[\w.-]+\.[a-zA-z]{2,4}/
```


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)
- [Links](#link)

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
^Hello          matches a string with `Hello`
World$          matches any string `World`
^Hello World$   matches the exact srting
goodbye         matches the exact string
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

- /d matches a single character any digit 0-9
- . matches any character
- /s matches a whitespace character
- /w matches a word character that is a-z
### The OR Operator

OR Operators matches a choice of expressions if you put the character representing the operator between any two characters in a regular expression, the result matches the union of strings that those two characters match.
- ``` | ```
- ``` [] ```

### Flags
Flags are optional parameters that can be added to plain expressions to make it search in different ways. Each flag is followed by a alphabetic character.
 - ```i```  - Insensitive, makes an expression case insensitive
 - ```m```  - Multi-line, when paired with (^$) will match a start and end line, rather than the whole string
 - ```g```  - Global, only returns the first match, after restarting it makes the expression search for all 
### Character Escapes
Escaped Characters are regular expressions that use ``` \ ``` that go in front of character classes.

- ``` \d ``` matches a single digits 0-9
- ``` \s ``` matches a single whitespace character
- ``` \U ``` matches a single character that is not uppercase
- ``` \z ``` matches a character at the end of a string before the break

### Bracket Expressions
Bracket Expressions are characters that are enclosed by brackets allowing users to match any character that is within the brackets. 
- [] any character within the brackets
- []% any character in the brackets that appears before the %
- [^] any string that does not have a letter that is within the brackets

## Author
I am a current student at the University of Denver in their full-stack coding bootcamp. In my free time I enjoy exploring colorado and spending time with my family. I've worked 4 years in the medical feild specializing in eating disorders.

## Links

GitHub: https://github.com/Hfranz1
GitHub Repo: https://github.com/Hfranz1/Regex-Tutorial
