# Vim Course By Free Code Camp
#### Remember, Lord always stay with you!

- youtube: [link](https://www.youtube.com/watch?v=RZ4p-saaQkc&t=22s)
- professor: Florian Dedov

## First of all
is recomment download one "Vim Cheat Sheet" 
for quit vim -> without save q! -> for save wq
only ! -> execute terminal commands
ps: !q doenst work, because "q" doenst terminal command

## Vim Modes

### Normal Mode
- normal mode: when you open a new file we are in the normal mode, in normal mode every key has its functionality
- key press "r" and type character for replace 
-  press 5 + keyDown, jump for 5 lines down.
- 15 + keyRight, jump for 15 characters to the right
- u: undo last operation (like ctrl + z)
- ctrl + R : re-do last undo
ps: you can combine with numbers, example: 3u, 3crtl+r

#### keybinds
##### Delete
- dw: delete word
- diw: delete in a word (same for de yank ex: yiw)
- delete/cut whole line: dd (in normal mode)
- delete/cut 6 lines: 6dd
- delete/cut 1 word: dw
- delete whole line and enter in the insert mode: cc
- d0: delete everything until the benginning
- d$: delete everything until the end of the line

#### Cursor movement
- 00/I: go to start of the line
- 0$: go to end of the line
- %: over the "{" move to "}"
- t*: move to after * 
- T*: move to before *
- gg: go to the top
- G: go to the end
- 123G: go to line 123
- :123: go to line 123
- zz: include down space (not new line, space only)

#### Copy
- c: copy(and delete) and enter to insert mode (you can combine with "w" and "i", ex: "ciw")
- ci(: copy and delete inside of the parameter
- y: only copy

#### nav into document
- jk: up/down
- hl: right/left
- w: jump for the next word
- b: before word
ps: this is userfull cause do you dont need leave the keybord chacters keys area.
you can combine numbers, j4, k5

### Visual mode
- in normal mode key press "v"
- for select just move the cursor
- copy: y (yanke)
- paste: p
- delete/cut: d
- ctrl + v: enter to the visual block mode

### insert mode
- for exit, key press "Esc"
- i: enter beside
- I: enter beginning of the line
- a: end the word
- A: end in the line
- o: enter in below the new line
- O: enter in above

## Settings
### Line Number
:set number
ps: line numbers can be combine with key bindings

#### Colorscheme
:colorscheme murphy -> this define "murphy" color scheme

#### Relative numbers
:set relativenumber -> userfull for change line numbers for navegation

#### set default settings
- config vim: ~/.vimrc

## Indentation and Formatting
> : in visual mode, indent for de left
< : indent for the right
= : if select, indent all
==: indent all block
=G: in the beggin of the document, indent all document

## Searching
/word : search "word", for to jump the next "word", press "n", for de previus, "N"

## Other important Shoutcuts

### Replacing same words
:%s/word/newWord

### Repeat last command
.

### See last commands
:reg

## Plugins
https://github.com/junegunn/vim-plug

