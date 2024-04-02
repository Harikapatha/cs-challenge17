# Title - components for Regex

Introductory paragraph (replace this with your text)
Describing below components for Regex - /^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/

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

### Anchors
- ^ asserts the start of the line.
- $ asserts the end of the line.

### Quantifiers
- ? matches the preceding element zero or one time.
- * matches the preceding element zero or more times.

### Grouping Constructs
- ( and ) are used for grouping and capturing.
- (https?:\/\/)? is a capturing group for the protocol part of the URL.
- ([\da-z\.-]+) captures the domain name part.
- ([a-z\.]{2,6}) captures the top-level domain.
- ([\/\w \.-]*)* captures the path part (including any additional slashes, words, spaces, dots, and hyphens).


### Bracket Expressions
- [...] defines a character class.
- [\da-z\.-] matches any digit, lowercase letter, period, or hyphen.

### Character Classes
- \d matches any digit.
- \w matches any word character (alphanumeric characters plus underscore).
- \. matches a period (escaped because period is a special character in regex).
- [a-z] matches any lowercase letter.


### The OR Operator
| acts as the OR operator, allowing for multiple options to be matched.

### Flags
There are no flags in this regex. Flags are used to modify how the regular expression engine processes the pattern.

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
- https://github.com/Harikapatha/cs-challenge17
