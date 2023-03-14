# Regex Tutorial

This Regular Expression tutorial was to be created to further let you help you understand special characters in sequence when trying to verify a search term. This will help you define the specific search pattern and when included with search algorithms, they are allowing you to validate input data. 

## Summary

The code will be giving you a tutorial for matching email and give examples of the components for regex. 

Matching an Email – /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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
The Anchors regx expression are ^. This is allowing the beginning of the string and the $ will allow the end of the string. 


### Quantifiers

The Quantifiers will be the + and it allows the email to be attached to the .com. 
the { } are also there to designate the minimum and maximum values of the groups.


### Grouping Constructs
([a-z0-9_\.-]+): this will be matching the users email address name.
([\da-z\.-]+): this will be matching the email service.
([a-z\.]{2,6}): this will be matching the .com part of the email.


### Bracket Expressions
the brackets will show characters that are to be mathed to one another. the pattern is allowing you to not need to OR operator if you are using the bracket expression.  this can be used to match a single element of collating elements. 

### Character Classes
this is going to be the set of characters that are going to be inside of the []. 
/d is the characters for matching the email after the @ in order to sign in. 

### The OR Operator

We are using the OR operator and matching the characters
a,b,c,ab,bc,ac,abc and they are all going to be valid matches. 


### Flags

Flags will be allowed to be outside of the / and its letting you know the start and finihs of the regex. There are 6 types in havascript, some commons ones are g, m, i.
g: the first match will be returned
m: multuline mode
i: case sensitivity search 

### Character Escapes

using the / will allow the character escapes and it will restore the code to its original meaning. 

## Author
Elizabeth Ramos
https://github.com/lizramos611