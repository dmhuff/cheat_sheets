UNIX Cheat Sheet
================

egrep
-----
- `egrep -r --include '*.txt' foo .`: Search for all text files containing "foo" recursively, starting in the current directory.

find & xargs
------------
- `find . -name '*.md' | xargs -I {} cp {} /somewhere/else`: Copy all markdown files in the current directory somewhere else.
