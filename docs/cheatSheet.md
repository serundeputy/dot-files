Helpful Vim Commands
====================

Vim
---

`$` move to the end of a line in command mode

`A` move to the end of a line in insert mode

`0` move to the beginning of a line in command mode

`dd` delete a line

`D` delete from the cursor to the end of a line

`d7j` delete 7 lines down from the cursor

`d12k` delete 12 lines up from the cursor

`dw` delete to the end of the word from cursor

`w` move cursor forward one word

`b` move cursor back one word

Copy and Paste
--------------

`y` copies a line
  - navigate cursor to where you want to paste (stay in command mode) then press `p`

`dd` cuts a line

Toggle some things
------------------

`:set nu!` ~ toggle line numbers

`:set list!` ~ toggle showing spaces and eol chars

VisualBlock
-----------

To select a VisualBlock of text: `Ctrl+Shift+v` then up or down arrow to the desired
nunmber of lines.
  - To select all the lines to the end of each of them: `Shift+v`
  - Then of course you can `y` or `d` to copy or cut
  
Nerdtree
--------

Nerdtree gives you a file browser in the left pane of your vim session.
You can toggle Nerdtreee open/closes with `Ctrl+n`

To navigate between panes of open editor:

`Ctrl+w` then
  - `l` to right pane
  - `j` to pane below
  - `k` to pane above
  - `h` to  left pane
