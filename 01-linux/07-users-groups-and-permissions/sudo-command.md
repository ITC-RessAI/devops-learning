# Sudo Command

## Overview
**sudo** lets a permitted user run a command with elevated (root) privileges, without logging in as root directly. It's the standard way to perform administrative tasks safely, since every action is logged and tied to the user who ran it.

---

## Key Learnings
- `sudo` runs a single command with root privileges, then reverts back
- Access is controlled through `/etc/sudoers`, edited safely with `visudo`
- Every `sudo` command is logged, unlike direct root logins
- `sudo` is generally safer than logging in as root for day-to-day admin tasks

---

## Commands Practised
### `sudo <command>`
Runs a single command with elevated privileges.

### `sudo -i`
Starts an interactive root shell.

### `visudo`
Safely edits the sudoers file with syntax checking.

---

## Reflection
Using `sudo` instead of logging in as root made me appreciate the accountability angle — every privileged action is traceable back to a specific user.
