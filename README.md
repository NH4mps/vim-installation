# vim-installation
Contains useful tips for vim text editor and some vimrc files with pluggins, mappings and other settings.

## MODES
### Command Mode
Command mode has a wide variety of commands and can do things that normal mode can’t do as easily. To enter command mode type ’:’ from normal mode and then type your command which should appear at the bottom of the window. For example, to do a global find and replace type :%s/foo/bar/g to replace all ‘foo’ with ‘bar’
#### Searching and replacement
Enter the normal mode, then use this hotkeys
- / искомый текст ↵ Enter — найти текст и переместиться к нему
- ? искомый текст ↵ Enter — то же самое, но искать с конца документа
- n — повторить поиск текста (сразу переместит к искомому тексту)
- N — повторить поиск назад (сразу переместит к искомому тексту)

### Replace Mode
Replace mode allows you replace existing text by directly typing over it. Before entering this mode, get into normal mode and put your cursor on top of the first character that you want to replace. Then press ‘R’ (capital R) to enter replace mode. Now whatever you type will replace the existing text. The cursor automatically moves to the next character just like in insert mode. The only difference is that every character you type will replace the existing one.

### Visual Mode
#### SELECTIONS, COPYINGS:
Insertion at the start of selected lines:
>Use Ctrl+V to enter visual block mode
>Move Up/Downto select the columns of text in the lines you want to comment.
>Then hit Shift+i and type the text you want to insert.
>Then hit Esc, wait 1 second and the inserted text will appear on every line.
>Also works with:
> - Shift+a (Insert after slected columns)
> - r (Replase selected symbols with inputted symbols)

### Useful keys for mode witching
- a -	append text after the cursor (switch to Insert mode)
- v -	switch to visual mode
- V	- switch to visual line mode

## SOME USEFUL HOTKEYS

### IN EDITOR SPACE SWITCHINGS:
- Ctrl + PgUp/PgDown - tab switching
### MOVING AROUND THE LINES:
- Shift + w - move cursor to the right until the first space
- Shift + b - move cursor to the left until the first space
- { - move cursor to the prev paragraph
- } - move cursor to the next paragraph
- 0 - beginning of line
- ^ - beginning of line
- $ - end of line
### MOVING AROUND THE SCREEN:
- Ctrl + d - move cursor half screen height down
- Ctrl + u - move cursor half screen height up
- Ctrl + f - move cursor to the bottom of the screen
- Ctrl + b - move cursor to the top of the screen
- G	- end of buffer
- gg - beginning of buffer
### PASTINGS:
- P	- paste at the cursor
- "+p -	paste from system clipboard after the cursor	
- "+P	- paste from system clipboard at the cursor

## Global and not global variables?
