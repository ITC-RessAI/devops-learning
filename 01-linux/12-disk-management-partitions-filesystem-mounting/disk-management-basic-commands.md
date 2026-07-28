# Disk Management – Basic Commands

## Overview
Before partitioning or formatting anything, it's essential to be able to inspect existing disks and their usage — this covers the core commands for viewing block devices and disk space.

---

## Key Learnings
- `lsblk` gives a quick tree view of all block devices and their partitions
- `df` shows disk space usage per mounted file system
- `du` shows disk usage of specific files or directories
- Checking existing disk layout before making changes avoids costly mistakes

---

## Commands Practised
### `lsblk`
Lists all block devices and their partitions in a tree structure.

### `df -h`
Shows disk space usage for mounted file systems, in human-readable format.

### `du -sh <directory>`
Shows the total disk usage of a specific directory.

---

## Reflection
Making `lsblk` and `df -h` a habit before touching any disk command gave me a safety check that avoided a couple of near-mistakes during the hands-on labs.
