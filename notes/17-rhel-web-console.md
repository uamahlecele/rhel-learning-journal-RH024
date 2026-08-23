# Managing Systems with the RHEL Web Console

## What is the Web Console
The RHEL web console (built on Cockpit) gives a browser-based GUI for managing a system — services, storage, networking, users, logs — useful when a visual view is faster than typing multiple commands, or for admins less comfortable in a terminal.

## Highlights
- Not a replacement for the command line, more a complementary view — good for quick checks like disk usage or service status without stacking several commands.
- Everything shown maps back to the same underlying tools covered earlier (systemctl, dnf, users/groups); it's a UI layer, not a separate system.
- Useful for onboarding team members less comfortable with the CLI without abandoning proper admin practices underneath.

## Terms I had to look up
- **Cockpit** — the actual project behind the RHEL web console, the browser-based system administration interface itself.