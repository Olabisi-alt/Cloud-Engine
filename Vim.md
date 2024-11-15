## The operational modes are:
- Normal Mode: The default mode, used for navigating and manipulating text.
- Insert Mode: Used to insert text.
- Visual Mode: Used to highlight and select text.
- Command Mode: Used to execute commands like saving, quitting, or searching.

## Basic Vim Workflow
When you open a file in Vim, it starts in Normal Mode. From here, you can move around and perform text operations. To edit text, you need to enter Insert Mode.

## Switching Modes
1. Normal Mode: Press Esc to return to Normal Mode from any other mode.
2. Insert Mode: Press i to enter Insert Mode and start typing text. Use Esc to exit Insert Mode.
3. Visual Mode: Press v to enter Visual Mode to highlight text.
4. Command Mode: From Normal Mode, press : to enter Command Mode.

## Moving Around in Normal Mode
- h, j, k, l: Move the cursor left, down, up, and right (alternatively, you can use the arrow keys).
- w: Move to the beginning of the next word.
- b: Move to the beginning of the previous word.
- 0: Move to the start of the current line.
- $: Move to the end of the current line.
- gg: Move to the beginning of the file.
- G: Move to the end of the file.

## Basic Editing Commands (Normal Mode)
- i: Insert text before the cursor.
- a: Insert text after the cursor.
- o: Insert a new line below the current line.
- O: Insert a new line above the current line.
- x: Delete the character under the cursor.
- dd: Delete the current line.
- yy: Yank (copy) the current line.
- p: Paste the copied or cut content after the cursor.
- u: Undo the last change.
- Ctrl + r: Redo the last undone change.

##  Saving and Exiting
- While in Command Mode (press : from Normal Mode):

- :w - Save the file.
- :q - Quit Vim.
- :wq or :x - Save and quit.
- :q! - Quit without saving changes

## Searching in Vim
- In Normal Mode, you can search for text:

- /text: Search for text (press n to go to the next occurrence and N to go to the previous one).
- ?text: Search backward for text.

## Visual Mode for Selecting Text
- Press v to enter Visual Mode, and use the arrow keys or h, j, k, l to select text.
- Press d to delete the selected text, or y to yank (copy) it.

##  Deleting and Changing Text
- d: Delete a selection or motion (e.g., dw deletes from the cursor to the next word).
- cw: Change (delete and enter Insert Mode) until the end of the word.

## Other Useful Commands
- :set number: Show line numbers.
- :set nonumber: Hide line numbers.
- :syntax on: Enable syntax highlighting.

## Exiting Without Saving
- :q! - Force quit without saving changes.

## Basic Example Workflow:
1. Open a file in Vim: vim filename.txt / vi filename.txt
2. Navigate using arrow keys or h, j, k, l.
3. Press i to enter Insert Mode and start typing.
4. Press Esc to return to Normal Mode.
5. Press :w to save the file.
6. Press :q to quit Vim.

## Learning More
- Type :help in Vim to access its built-in help system.
