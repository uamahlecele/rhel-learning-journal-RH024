# Organizing Local Users and Groups
 
## What are Users and Groups
Every process and file on Linux belongs to a user and a group — this is the foundation that file permissions build on top of. Users can belong to one primary group and multiple secondary groups.
 
## Highlights
- `useradd -m <name>` creates a user with a home directory; `passwd <name>` sets their password.
- `usermod -aG <group> <user>` adds a user to a group — forgetting the `-a` flag wipes their other group memberships instead of adding to them.
- `id <user>` shows UID, GID, and all group memberships at a glance.
- `/etc/passwd` and `/etc/group` are just plain text files holding this information, nothing magic about them.
## Terms I had to look up
- **UID/GID** — the numeric ID behind a username or group name; the name is just a friendly label mapped to a number.
- **Primary vs secondary group** — the primary group is the default for anything a user creates, secondary groups grant additional access on top.