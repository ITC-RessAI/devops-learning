# Managing Services in Linux

## Overview
**Managing Services** covers using `systemctl` to start, stop, enable, and check the status of services — the standard way to control daemons on a systemd-based Linux system.

---

## Key Learnings
- `systemctl` is the primary tool for managing services under systemd
- Services can be started/stopped immediately, and separately enabled/disabled at boot
- Checking service status is essential for troubleshooting failed or misbehaving services
- Logs for a service can be viewed through `journalctl`

---

## Commands Practised
### `systemctl start <service>`
Starts a service immediately.

### `systemctl enable <service>`
Configures a service to start automatically at boot.

### `systemctl status <service>`
Shows whether a service is running, along with recent log output.

### `systemctl stop <service>`
Stops a running service.

---

## Reflection
Practising the full start/stop/enable/status cycle on a real service made `systemctl` feel like a tool I'd genuinely reach for on the job, not just a command to memorise for an exam.
