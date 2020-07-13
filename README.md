# Alloy-VSCode README

This extention provides very basic syntax high-lighting for Alloy Analyzer(<http://alloy.mit.edu/alloy/index.html>).

There might be some bugs and could not handle all of the situations.

## Features

Syntax Highlighting for Alloy Modeling Language

## Requirements

Nothing

## Known Issues

Some (maybe not) complex expressions might not be able to colorize as expected.

## Release Notes

### 0.1.5

Add highlight to "seq" and "else", thanks for Ferhat Erata.

### 0.1.4

Added support for Alloy code blocks in markdown

### 0.1.3

Fix some issues, thanks for Arash Sahebolamri.

### 0.1.2

Now support self defined module and functions.

### 0.1.1

Now support self defined module and functions.

### 0.1.0

1. Totally remove the tmLanguage file extracted from HiroakiMikami/atom-alloy.
2. Write a totally new tmLanguage file from scratch based on the Alloy Language Reference.
    * Using a multi-level approach to reduce the pattern matching times and enhance the coverage.
    * Reduce the miss colorizing dramatically.
    * More neat for further refactoring.
3. Add support to built-in functions.
4. Fix issues.

### 0.0.3

Add the link to the original tmLanguage file extracted from HiroakiMikami/atom-alloy(<https://github.com/HiroakiMikami/atom-alloy>).

### 0.0.2

Fix a minor typo.

### 0.0.1

Initial Release.
