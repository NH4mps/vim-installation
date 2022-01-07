# vim-installation
Contains useful tips for vim text editor and some vimrc files with pluggins, mappings and other settings.

================== USEFUL HOTKEYS ==================

MODE SWITCHINGS:
a -	append text after the cursor (switch to Inset mode)
v -	switch to visual mode	V	switch to visual line mode

IN EDITOR SPACE SWITCHINGS:
Ctrl + PgUp/PgDown - tab switching

SEARCHING
/ искомый текст ↵ Enter — найти текст и переместиться к нему
? искомый текст ↵ Enter — то же самое, но искать с конца документа
n — повторить поиск текста (сразу переместит к искомому тексту)
N — повторить поиск назад (сразу переместит к искомому тексту)

MOVING AROUND THE LINES:
Shift + w - move cursor to the right until the first space
Shift + b - move cursor to the left until the first space
{ - move cursor to the prev paragraph
} - move cursor to the next paragraph
0 - beginning of line
^ - beginning of line
$ - end of line

MOVING AROUND THE SCREEN:
Ctrl + d - move cursor half screen height down
Ctrl + u - move cursor half screen height up
Ctrl + f - move cursor to the bottom of the screen
Ctrl + b - move cursor to the top of the screen
G	- end of buffer
gg - beginning of buffer

PASTINGS:
P	- paste at the cursor
"+p -	paste from system clipboard after the cursor	
"+P	- paste from system clipboard at the cursor

SELECTIONS, COPYINGS:
INSERTION AT THE START OF SELECTED LINES
Use Ctrl+V to enter visual block mode
Move Up/Downto select the columns of text in the lines you want to comment.
Then hit Shift+i and type the text you want to insert.
Then hit Esc, wait 1 second and the inserted text will appear on every line.
I guess the same trick can be done with SHIFT + P.
