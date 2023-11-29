# Regex Tutorial: Matching Hex Values

## Summary
This tutorial meticulously explains the regular expression `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/` designed to match Hex Color Codes.

Hexadecimal codes are comprised of 6 alphanumeric characters and serve as representations for colors. The regular expression yields a '#' symbol followed by either a 6 or 3-character code, encompassing lowercase letters (a-f) or numbers (0-9).

## Table of Contents
- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Author](#author)

## Regex Components

### Anchors
In the given regular expression, `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`
, both the caret and the dollar sign serve as anchors, delineating the pattern within the example string.

* The ^ caret denotes the beginning of the string to which the regex pattern is applied. It ensures that the pattern matches only at the start of the string.

* The # Number Sign immediately following the ^ caret is a literal character. It is mandatory at the beginning of the string; thus, a # Number Sign must be present at the start.

* The $ dollar sign, located at the end of the regex pattern, functions as an anchor as well. It matches only at the end of the string to which the pattern is applied, indicating the conclusion of the string.

This regular expression also incorporates quantifiers, such as {6} and {3}, specifying the quantity of characters that must match the given pattern.
### Quantifiers
Within the given pattern `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`:

The $ (Dollar Sign), denotes that the # (Number Sign) will either match 0 or 1 time.

{6} specifies that the preceding token [a-f0-9] is anticipated to consist of exactly 6 characters within that set.

{3} indicates that the preceding token [a-f0-9] should precisely comprise 3 characters within that set.
### OR Operator

### Character Classes


### Grouping and Capturing


### Greedy and Lazy Match


### Boundaries


## Author
Micah, a Michigan State University coding bootcamp student. 
Check out [my GitHub](https://github.com/G303K) for more of my work.