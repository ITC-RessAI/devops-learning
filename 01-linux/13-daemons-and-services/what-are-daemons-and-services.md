# What are Daemons and Services?

## Overview
A **daemon** is a background process that runs without direct user interaction, typically providing a system service — things like web servers, SSH access, or logging. **Services** are how systemd-based Linux systems manage the lifecycle of these daemons: starting, stopping, and monitoring them.

---

## Key Learnings
- Daemons run in the background, usually starting at boot
- Daemon process names conventionally end in "d" (e.g. `sshd`, `crond`)
- systemd is the modern init system managing services on most Linux distributions
- A "service" is the systemd unit that controls a daemon's lifecycle

---

## Reflection
Connecting "daemon" (the running background process) to "service" (the systemd unit managing it) resolved a distinction I'd been fuzzy on.
