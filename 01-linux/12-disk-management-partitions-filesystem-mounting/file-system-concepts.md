# File System Concepts

## Overview
A **file system** defines how data is organized and stored on a partition — Linux supports several, like `ext4` and `xfs`, each with different tradeoffs. A partition isn't usable for storing files until it has been formatted with a file system.

---

## Key Learnings
- A partition must be formatted with a file system before it can store files
- `ext4` is a common general-purpose Linux file system
- `xfs` is often used for large-scale or high-performance storage
- Formatting a partition erases any existing data on it

---

## Commands Practised
### `mkfs.ext4 /dev/sdX1`
Formats a partition with the ext4 file system.

### `mkfs.xfs /dev/sdX1`
Formats a partition with the xfs file system.

### `blkid`
Displays the file system type and UUID of a partition.

---

## Reflection
Formatting a test partition and then checking it with `blkid` made file system types feel concrete rather than abstract labels.
