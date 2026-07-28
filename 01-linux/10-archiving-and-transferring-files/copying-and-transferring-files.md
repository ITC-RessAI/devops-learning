# Copying & Transferring Files

## Overview
**Copying & Transferring Files** covers moving files between systems, not just within one — using `scp` for straightforward secure copies and `rsync` for more efficient, resumable transfers.

---

## Key Learnings
- `scp` securely copies files between local and remote systems over SSH
- `rsync` only transfers the differences between source and destination, making it faster for repeated transfers
- Both tools rely on SSH for secure, authenticated transfers
- `rsync` supports resuming interrupted transfers, `scp` does not

---

## Commands Practised
### `scp file user@host:/path`
Copies a local file to a remote system over SSH.

### `scp user@host:/path file`
Copies a file from a remote system to the local machine.

### `rsync -avz source/ user@host:/destination/`
Efficiently syncs a directory to a remote system, only transferring changes.

---

## Reflection
Timing `rsync` against `scp` on a repeated transfer made the efficiency difference obvious — `rsync` is clearly the better choice once files are already partially in sync.
