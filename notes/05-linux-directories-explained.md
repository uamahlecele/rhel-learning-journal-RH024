# Linux Directories Explained

## What is the Directory Structure
Linux follows a standard layout (the Filesystem Hierarchy Standard) so the same folders mean the same thing across distros — `/etc` is always config, `/var` is always variable data, and so on. Once this clicks, navigating any unfamiliar Linux box gets much less intimidating.

## Highlights
- `/etc` — system-wide configuration files.
- `/var` — variable data like logs and caches; `/var/log` especially matters for troubleshooting.
- `/home` — personal user directories, separate from `/root`, which is specifically the root user's home.
- `/tmp` — temporary storage, cleared on reboot, never for anything important.
- `/opt` — optional third-party software, kept separate from the base system.

## Terms I had to look up
- **FHS (Filesystem Hierarchy Standard)** — the spec defining this directory layout so it stays consistent across Linux distributions.
