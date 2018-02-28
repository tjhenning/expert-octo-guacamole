# X-Team 06 Style Guide

Our team will utilize the style guide used in CS 300 at University of Wisconsin-Madison. This document can be found at the following <a href="http://cs300-www.cs.wisc.edu/wp/index.php/2017/08/15/cs300-java-style-guide/">link</a>. Several key components are discussed below:

## Naming conventions

Further information on naming conventions can be found within the CS 300 Style Guide. This information is summarized below:

### Summary
* Class and Interface are written in UpperCamelCase and are typically nouns or noun phrases
* Methods, Fields, and Local Variable names are written in lowerCamelCase
  * Method names are typically verbs or verb phrases
    * ex. getHeight
  * Field and Local Variable names are typically nouns or noun phrases
    * ex. numberOfItems
* Constants are written in CONSTANT_CASE
  * ex. MAX_SIZE

## Commenting style for public and private members of a class or interface:

Further information on commenting style can be found within the CS 300 Style Guide. This information is summarized below:

### Summary

* All Classes and Methods (including Constructors) must have JavaDoc headers
* Either single line (//...) or multi-line (/\*...\*/) may be used
  * Provide descriptive comments for field and variable declarations
  * Inline comments will be used to describe high level algorithm choices
  
* Coding Style (brackets, horizontal, and vertical spacing) for:
  * if statements
  * switch statement
    * Brackets are put on same line as switch statement
    * The body of the switch statement is indented like all other code blocks
  * while loops
  * for loops
  * enhanced for loops
