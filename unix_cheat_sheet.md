UNIX Cheat Sheet
================

egrep
-----

- `egrep -r --include '*.txt' foo .`: Search for all text files containing "foo" recursively, starting in the current directory.


vim
---

- `:%s/foo/bar/gci`: Find an replace "foo" with "bar", ask for confirmation, case insensitive.

- `V`: Select lines.
- `.`: Repeat last command.

### History ###
- `:his`: List command history.
- `:his /`: List search history.
- Command Line Window
    - `q:`: Commands.
    - `q/`: Searches.
- `: up-arrow`: Scroll through history.
- `/ up-arrow`: Scroll through searches.

### Shell Commands ###
- `:! ls`: Execute shell command.
- `:r ! ls`: Execute shell command, put output in current buffeR.

### Indentation ###

- `<`: Unindent line.
- `>`: Indent line.
- `5>>`: Indent 5 lines.
- `>%`: Indent curly brace block.
