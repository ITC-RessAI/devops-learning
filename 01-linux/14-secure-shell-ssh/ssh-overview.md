# Secure Shell (SSH) Overview

## Overview
**SSH** provides a secure, encrypted way to connect to and manage a remote Linux system over a network. It's the standard method for remote administration, replacing older, unencrypted protocols like Telnet.

---

## Key Learnings
- SSH encrypts the entire session, protecting credentials and data in transit
- The default SSH port is 22
- SSH can be used for remote shell access, file transfer (via `scp`/`sftp`), and port forwarding
- `sshd` is the daemon that listens for incoming SSH connections on the server side

---

## Commands Practised
### `ssh user@host`
Connects to a remote system over SSH using a username and password (or key).

### `ssh -p <port> user@host`
Connects to a remote system on a non-default SSH port.

---

## Reflection
Connecting to a remote EC2 instance over SSH for the first time made the whole "remote server management" side of DevOps feel real instead of theoretical.
