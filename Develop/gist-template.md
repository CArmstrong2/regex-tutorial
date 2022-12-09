# Regex Tutorial

Regex is a powerful pattern-matching tool. In this brief tutorial, I will explain how to use regex to match videos files with the most common video file extensions.

## Summary

To match a file with a common video file extension, we will use the following regular expression:

`/\.(mp4|avi|mov|webm|wmv|mpg)$/`

This will match any file ending in a period and one of the extensions in parantheses (eg: MyVideo.mp4, MyCoolVideo.webm, x.mov). The way it works is simple.

First, the entire expression is wrapped in forward slashes.  `//`

Next, we want to match a period. `/./`

We want to ensure that we are matching a literal, escaped period, so we put a backslash immediate before it. `/\./`

Now, we match the characters of a file extension. To match only .mp4 files, we do the following. `/\.mp4/`

However, we only want to match the very end of the filename, where the file extension is located, so we will use $ to signify that. `/\.mp4$/`

Finally, if we want to match multiple characters or strings, we wrap what we want to match in parantheses, and separate them with vertical bars. `/\.(mp4|mov|mpg)$/`


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

    Anchors don't match any characters, but instead assert something about the string or matching process, such as matching at the beginning of a line, but not anywhere else.

    The following are regex anchors:

    ^ - beginning of string/line
    $ - end of string/line
    \A - absolute beginning of string
    \z - absolute end of string
    \Z - end of string

### Quantifiers

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
