# Managing Networking

## What is NetworkManager
Networking on RHEL is handled by NetworkManager, a background service, with nmcli as its command-line front end and nmtui as a text-based UI version for quicker manual changes.

## Highlights
- ip addr is the modern replacement for the older ifconfig — worth unlearning tutorials that still reference it.
- nmcli device status and nmcli connection show give a quick read on interfaces and configured connections.
- Static vs DHCP matters most for servers, since most production systems use static IPs so they don't change on reboot.

## Terms I had to look up
- **NetworkManager** — the background service actually managing connections on RHEL; nmcli/nmtui are just interfaces to control it, not the thing doing the work itself.