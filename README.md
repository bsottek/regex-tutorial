# regex-tutorial

This is meant to be a quick overview about regular expressions (aka REGEX) and how you can put them to good use. They can be as simple or as complicated as you make them, so let's dive in.

## Definition:
A sequence of characters that specifies a search pattern. Usually such patterns are used by string-searching algorithms for "find" or "find and replace" operations on strings, or for input validation.

## Contents:
* [Basics](#basics)
* [Usage](#usage)
* [Resources](#resources)


## Basics
There are several core concepts or operators to regex. Here are a few:
* Boolean "or" - a vertical bar character <|> denotes an "or" statement --> (up|down) matches "up" or "down"
* Grouping - Parentheses denote the scope of the included operators. --> gr(e|a)y would match either "grey" or "gray"
* Quantifiers - operators that specify the number of times a character can occur to match --> "?" denotes 0 or 1 occurences while "*" denotes 0 or more.
* Wildcard - a period matches any otherwise unspecified character --> a.b would match anything with a on one end and b on the other.


## Usage
Regex is used in a variaty of applications but here are a few notable ones:
* Data validation
* Data scraping
* Web scraping
* Data wrangling
* Parsing
* Syntax highlighting
* Small search functions


## Resources
While learning regex can be overwhelming, it's a valuable skill with lots of open-source support. Any of the resources below (and many more) could prove valuable in your learning process. Give them a try and good luck!

* https://regex101.com/ - an educational, web-based IDE for regex
* https://regexone.com/ - a lightweight, free tutorial with hands-on examples
* https://regexr.com/ - a regex tester with syntax highlighting, pattern suggestions, and immediate execution for fine-tuning results.
