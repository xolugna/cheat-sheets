# useful

```sh
# https://vim.rtorr.com/

# move
H - move to top of screen
M - move to middle of screen
L - move to bottom of screen
0 - jump to the start of the line
^ - jump to the first non-blank character of the line
$ - jump to the end of the line
gg - go to the first line of the document
G - go to the last line of the document
} - jump to next paragraph (or function/block, when editing code)
{ - jump to previous paragraph (or function/block, when editing code)

# edit
u - undo
Ctrl + r - redo
. - repeat last command

# search and replace
/pattern - search for pattern
?pattern - search backward for pattern
n - repeat search in same direction
N - repeat search in opposite direction
:%s/old/new/g - replace all old with new throughout file
:%s/old/new/gc - replace all old with new throughout file with confirmations
%s/// - it search for whatever you last searched for

# execute commands
:%! sort - execute command in current file
: tabn number - move between tabs
:tabnew |read !sort -u \# - new tab with sorted current file

```