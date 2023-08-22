# Title Regex Tutorial- Email edition
This tutorial will go through how to break down a regular expression in order to find an email
## Summary
Email Regex
 /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)

- [Character Classes](#character-classes)

- [Grouping](#grouping)
- [Bracket Expressions](#bracket-expressions)

- [Sourcess](#sources)
- [Author](#author)


## Regex Components

 /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
### Anchors

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

^ is the beginning of the text and $ is the end of the text. These characters are considered the anchors. 
### Quantifiers

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

Used to tell how many times a part of a regular expression should be repeated - how many times you would like (an individual character, a character class or a sub-expression) to be repeated 

+ operator : connects users email name + email service+ .com
 
ex:
{2,6} which allows a match range of 2-6 characters for the character set [a-z\.]

{n, x} - this matches the pattern starting with a minimum number (n) of times all the way to a maximum (x) number of times


### Character Sets/Classes

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

Defines a set of characters within square brackets [] . Identifies the characters that will match a single character to the given input string. 
### Grouping

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

What is in the () is known as a sub-expression, which captures group matches and from there it will match character sequence for possible reuse
([a-z0-9_\.-]+)
([\da-z\.-]+)
([a-z\.]{2,6})

### Bracket Expressions


/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

[]- anything inside of this represents a range of characters that we want to match . 
[a-z0-9_\.-]

a-z : meaning it will match any letter a-z 
0-9: meaning it will match a single digit in these parameters


### Sources

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
