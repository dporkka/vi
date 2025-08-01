# How to use the vi text editor

## 1. Launch vi

```vi filename```
If the file doesn’t exist, vi creates it.

## 2. Modes

Normal (command) mode: navigate, delete, yank, paste

Insert mode: type text

Visual mode: select blocks of text

By default you start in Normal mode.

## 3. Switching to Insert mode

i – insert before cursor

I – insert at start of line

a – append after cursor

A – append at end of line

o – open new line below

O – open new line above

Press Esc to return to Normal mode.

4. Moving the cursor (Normal mode)

h ← left

j ↓ down

k ↑ up

l → right

w – jump to start of next word

b – back to start of previous word

0 – to beginning of line

$ – to end of line

G – to end of file

gg – to start of file

5. Editing commands (Normal mode)

x – delete character under cursor

dd – delete entire line

dw – delete to end of word

u – undo last change

Ctrl + r – redo

yy – yank (copy) current line

yw – yank word

p – paste after cursor

P – paste before cursor

6. Searching and replacing

/pattern – search forward

?pattern – search backward

n – next match

N – previous match

:%s/old/new/g – replace all “old” with “new” in the file

:5,10s/old/new/g – replace in lines 5–10

## 7. Saving and quitting

:w – write (save)

:w filename – save as a new name

:q – quit (fails if there are unsaved changes)

:q! – quit without saving

:wq or ZZ – write and quit

## 8. Helpful tips

To see line numbers:

vim
Copy
Edit
:set number
To toggle between modes quickly, remember Esc brings you back to Normal.

**If you ever feel “stuck,” press Esc a few times, then use :q! to exit without saving.**

