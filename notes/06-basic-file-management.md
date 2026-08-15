# Basic File Management

## What is File Management
The core set of commands for creating, moving, copying, viewing, and deleting files — this is muscle-memory territory more than conceptual, but it underlies everything else done on the command line.

## Highlights
- `mv` doubles as rename — there's no separate rename command for the basic case.
- `rm` has no recycle bin; deleted means gone, no undo. `rm -rf` should be treated with real caution.
- `less` beats `cat` for big files since it lets you scroll instead of dumping everything to screen at once.
- `find /path -name "*.log"` is the go-to for locating files by pattern instead of manually browsing.

## Terms I had to look up
- **Recursive (`-r`)** — applying a command to a directory and everything inside it, not just the top-level item.