## Documentation
Linux ships with its own set of documantation built in, so before searching the web, the answer is often already on the machine, accessed through the shell. 

"man pages" are the core of this — structured manuals for nearly every command, config file, and system call.
 
## How to utilise man pages

- `man <command>` gives the full manual; `<command> --help` gives a faster, shorter cheat-sheet version.
- `man -k <keyword>` searches by keyword when I don't know the exact command name.
- Man pages are split into numbered sections (1 = commands, 5 = file formats, 8 = admin commands) — `man 5 passwd` is different from `man passwd`.

- You hit "q" to exit out of a man-page!

## Terms I had to look up
- **Man page sections** — man pages are categorized by type (commands, file formats, syscalls, etc.), and the same word can point to different pages depending on the section number.
 
## Terminal Session

![terminal session](documentation.png)