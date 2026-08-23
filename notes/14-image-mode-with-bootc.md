# Using Image Mode with Bootc

## What is Image Mode
Instead of managing RHEL package-by-package the traditional way, Image Mode treats the entire OS as a container image that gets built, versioned, and deployed. bootc is the tool that handles booting and updating a system from these images.

## Highlights
- Applies container/image thinking — build once, version it, deploy everywhere — to the whole OS, not just applications running on it.
- Updates become atomic: you switch to a new, fully-built image version rather than patching a live system piece by piece, making rollbacks cleaner.
- A shift from treating a server as something you maintain over time to treating it as a disposable, reproducible artifact.

## Terms I had to look up
- **bootc** — the tool for booting and managing "bootable containers," OS images built and deployed the same way container images are.
- **Atomic update** — an update that either fully applies or doesn't apply at all, avoiding a half-updated, broken state.