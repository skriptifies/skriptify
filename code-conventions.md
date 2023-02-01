# Code Conventions

## Malicious Code
No contributions should contain malicious code designed to harm the user or their machine. 

## Code Style

### Formatting
* All scripts should be using spacing of FOUR spaces (NOT a tab)
** No spacing on empty lines
* Seperate each function/event/trigger with a line
* When splitting a string into multiple combined strings, spaces should be after the first string (ex: "This is a " + {string} + ".")
* All scripts should include comments with a description, the authors, dependencies and example usage, ex: 
```
# Description: Does stuff
# Authors: TheCodingDuck
# Dependencies: Sk-Bee (https://github.com/ShaneBeee/SkBee/releases), Skript-Reflect (https://github.com/TPGamesNL/skript-reflect/releases/)
# Example usage: send "hi" to player << THIS IS OPTIONAL. You may also optionally add more than one example usage.
```
* When using multiple lines of code for an example, for all lines following the first add a \# followed by spacing until equal with the start of the line above it
* 2 lines of spacing after information provided for the script (description, authors, dependencies, example usage, etc.)

### Naming
* Script files should be named in `UpperCamelCase` (AKA `PascalCase`)
* Variables and functions should be named in `camelCase`

### Comments
* Comments should be used to explain *why* you are doing things instead of *how* you are doing them, though you can do both
* Comments should be wrote in English, following the main grammar rules.
* The first letter of comments should be capitalized
* Comments should always have a space between the \# and the comment

## Compatibility
* All contributions should be tested on the latest version of Skript
* If editing an outdated script, update it to work with the latest version of Skript and any addon it requires (when possible)
