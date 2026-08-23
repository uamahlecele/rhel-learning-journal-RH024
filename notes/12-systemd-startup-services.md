# Managing System Startup Services with Systemd

## What is Systemd
Systemd is what boots RHEL and manages every service running on it, with systemctl as the main command for checking, starting, stopping, and enabling services.

## Highlights
- start/stop affects a service right now; enable/disable affects whether it starts on the next reboot — these are independent settings.
- systemctl status <service> gives current state plus recent logs in one place.
- journalctl -u <service> filters logs to just that service, faster than digging through separate log files.
- Services are defined by "unit files," which is where the name systemd comes from — everything is a managed unit.

## Terms I had to look up
- **Unit file** — the config file telling systemd how to start, stop, and manage a given service.
- **Enabled vs active** — enabled means it will start on boot, active means it's currently running; a service can be one without the other.