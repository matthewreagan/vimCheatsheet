# Vim Commands

## Navigation

- `.`		Repeats the last command
- `h,j,k,l`	Move cursor (left, down, up, right)
- `<Esc>`		Switches modes
- `i`		Interactive mode
- `a`		Interactive mode, append after cursor
- `A`		Interactive mode, append at end of line	(equivalent to `$a`)
- `o`		Interactive mode, inserting new line (equivalent to `A<return>`)
- `O`		Interactive mode, inserting previous line (equivalent to `ko`)
- `s`		Interactive mode, after deleting character (equivalent to `xi`)
- `w`   Move to start of next word
- `e`   Move to end of current word
- `b`   Move back to start of current word

## Finding, cursor movement

- `f<char>`	Scan line for next occurrence of <char>
- `F<char>`	Scan line for previous occurrence of <char>
- `;`		Repeats the last `f` command
- `,`		Repeats the last `f` command in reverse direction

## Finding, replacing

- `/<pattern>`	Scans document for next <pattern>
- `?<pattern>`	Scans document for prev <pattern>
- `*`		Scans document for current word under cursor
- `n`		Scans for next occurrence (of last search <pattern>)
- `N`		Scans for previous occurrence (of last search <pattern>)
- `:s/<X>/<Y>`	Replaces X with Y (current line)
- `:s/<X>/<Y>/g`  Replaces X with Y (document)
- `&`		Repeats last substitution

## Undo, Redo
- `u`		Undo
- `Cntl-R`	Redo 
