# grep-go

## Project Abstract

### This project is a from-scratch implementation of a regular expression (regex) engine, modeled after the functionality of the classic CLI tool grep. It explores how pattern matching engines work under the hood — including parsing, backtracking, and matching complex regex patterns.

### Throughout the project, the engine evolves from matching literal characters to supporting advanced features like quantifiers, anchors, alternation, and backreferences.

- Key Features & Learning Milestones
- Match literal characters, digits, and alphanumeric input
- Support positive and negative character classes
- Combine multiple character classes in one pattern
- Implement start (^) and end ($) of string anchors
- Handle quantifiers like + (one or more) and ? (zero or one)
- Support wildcard . and alternation using |
- Parse and evaluate backreferences (single, multiple, and nested)

### I'm building this project to better understand the inner mechanics of pattern matching, recursive parsing, and how tools like grep, sed, and programming language regex engines are implemented at a low level.
