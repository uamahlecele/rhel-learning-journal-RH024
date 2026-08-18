# Managing Software and Updates

## What is DNF
RHEL uses `dnf` (built on top of RPM) to install, update, and remove software — the same idea as `apt` on Debian/Ubuntu, just different syntax and package format underneath.

## Highlights
- `dnf install <package>` handles dependencies automatically, pulling in whatever the package needs without manual chasing.
- `dnf search <term>` and `dnf info <package>` help evaluate a package before installing it.
- `dnf list installed` and `rpm -qa` both show what's currently installed, one via dnf, one via RPM directly.
- Repositories (repos) are where packages actually come from — subscription status affects which repos are available on a real RHEL system.

## Terms I had to look up
- **RPM vs DNF** — RPM is the low-level package format/tool, DNF is the higher-level manager that adds dependency resolution and repo handling on top of it.
- **Repository (repo)** — a remote source of packages that dnf pulls from.