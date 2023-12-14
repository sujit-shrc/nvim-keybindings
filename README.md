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

### Custom Keybindings:

- `Ctrl + h`: Select file tree
- `Ctrl + l`: Select file editor
- `Shift + k`: View built-in manual docs of a particular keyword
- `Ctrl + k`: Exit from manual docs
- `Shift + h`: Left editor tab
- `Shift + l`: Right editor tab
- `Alt + j`: Move current line up
- `Alt + k`: Move current line down
- `gg=G`: Reindent entire file
- `gc`: Comment selected (use `gcgc` to uncomment block)
- `%`: Jump to the other bracket of the current block
- `_`: Jump to the first non-blank character on the line
- `$`: Jump to the last non-blank character on the line
- `0`: Jump to the start of the line
- `\text`: Search for text, `n` for next occurrence, `N` for the previous
- `f"`: Find the first ", jump to it with the right arrow
- `ci"`: Delete and start editing inside the next string literal
- `vi"`: Select inside the next string literal
- `viw`: Select the current word
- `di"`: Delete inside the next string literal
- `u`: Undo
- `Ctrl + r`: Redo
- `ma`: Set local mark a
- `mA`: Set global mark A
- `` (backtick): List marks
- ``a`: Go to mark a

### File Explorer Keybindings:

- `Space + e`: Toggle File Explorer
- `a`: Add a new file
- `d`: Remove a file
- `o`: Open a file and stay in file explorer
- `j`: Move down
- `k`: Move up
- `l`: Open file and move to editor
- `h`: Minimize folder
- `Ctrl + l`: Jump to editor
- `Ctrl + h`: Jump to file explorer

### Visual Mode Keybindings:

- `v`: Character mode
- `V`: Line mode
- `Ctrl + v`: Block mode
- `u`: Lowercase
- `U`: Uppercase
- `d`: Delete
- `c`: Change
- `y`: Yank
- `>`: Indent
- `<`: Dedent

### Neo-tree Keybindings:

- `r`: Rename
- `m`: Move
- `o`: Order by
- `i`: File details
- `v`: Available shortcuts
- `Ctrl + rarrow`: Expand tree to the right
- `Shift + h`: Toggle show hidden files

### Tmux Keybindings:

- `Ctrl + b + %`: Vertical split
- `Ctrl + b + "`: Horizontal split
- `Ctrl + b + x`: Close current panel
- `Ctrl + b + q`: Show panel nums
- `Ctrl + b + q + 1`: Switch to panel 1
