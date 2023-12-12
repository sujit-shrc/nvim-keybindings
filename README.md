### Basic Movement:

- `h`: Move left
- `j`: Move down
- `k`: Move up
- `l`: Move right
- `w`: Move to the beginning of the next word
- `b`: Move to the beginning of the previous word
- `e`: Move to the end of the current word
- `gg`: Go to the beginning of the file
- `G`: Go to the end of the file
- `0`: Move to the beginning of the line
- `$`: Move to the end of the line
- `^`: Move to the first non-blank character of the line

### Editing:

- `i`: Enter insert mode before the cursor
- `I`: Enter insert mode at the beginning of the line
- `a`: Enter insert mode after the cursor
- `A`: Enter insert mode at the end of the line
- `o`: Open a new line below the current line and enter insert mode
- `O`: Open a new line above the current line and enter insert mode
- `x`: Delete the character under the cursor
- `dd`: Delete the current line
- `yy`: Yank (copy) the current line
- `p`: Paste the yanked or deleted text after the cursor
- `u`: Undo
- `Ctrl + r`: Redo

### Visual Mode:

- `v`: Enter visual mode to select characters
- `V`: Enter visual line mode to select lines
- `Ctrl + v`: Enter visual block mode to select a block of text

### Searching:

- `/`: Start searching forward
- `?`: Start searching backward
- `n`: Move to the next search result
- `N`: Move to the previous search result

### Save and Quit:

- `:w`: Save the current file
- `:q`: Quit (close) the current file
- `:wq` or `ZZ`: Save and quit
- `:q!`: Quit without saving

### Other Useful Commands:

- `:help [command]`: Open help for a specific command
- `:e [filename]`: Open a new file
- `:bnext` and `:bprev`: Switch between open buffers
- `:sp [filename]`: Split the window horizontally
