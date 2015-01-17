Vim Cheatsheet
==============

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

### File Explorer ###
- `:e.`: Open in current working directory.
- `:E`: Open in directory of current file.
- References
    - <http://vimcasts.org/episodes/the-file-explorer/>

### Shell Commands ###
- `:! ls`: Execute shell command.
- `:r ! ls`: Execute shell command, put output in current buffer.

### Splits ###
- `:sp`: Create horizontal split.
- `:vsp`: Create vertical split.
- `:help splits`: Get help.
- `ctrl+w j`: Move cursor down a split (uses standard movement keys).
- References
    - <http://robots.thoughtbot.com/vim-splits-move-faster-and-more-naturally>

### Indentation ###

- `<`: Unindent line.
- `>`: Indent line.
- `5>>`: Indent 5 lines.
- `>%`: Indent curly brace block.

