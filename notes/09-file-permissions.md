# File Permissions

## What are File Permissions
Every file has three sets of permissions — owner, group, and everyone else — and three types of access: read, write, execute. Reading `ls -l` output stops looking like noise once this pattern clicks.

## Highlights
- `-rwxr-xr--` breaks down as owner (`rwx`), group (`r-x`), other (`r--`), after the leading file-type character.
- Numeric permissions aren't arbitrary: 4 = read, 2 = write, 1 = execute, added per category. `755` = owner full access, group and other read/execute.
- On directories, the execute bit means "can enter/traverse," not "can run as a program" — different meaning than execute on a regular file.
- `chmod` changes permissions, `chown user:group` changes ownership.

## Terms I had to look up
- **Execute bit on directories** — grants the ability to `cd` into a directory, separate from read (list contents) and write (modify contents).