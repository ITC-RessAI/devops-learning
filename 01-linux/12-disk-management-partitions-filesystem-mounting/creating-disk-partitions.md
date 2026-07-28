# Creating Disk Partitions

## Overview
**Creating Disk Partitions** covers actually building new partitions on a disk, using either the classic `fdisk`/`gdisk` tools or the more modern `parted`, depending on whether the target is an MBR or GPT disk.

---

## Key Learnings
- `fdisk` is used for MBR partition tables, `gdisk` for GPT
- `parted` supports both, and works with disks larger than the MBR 2TB limit
- Creating a partition doesn't format it — that's a separate step
- Partition changes should always be verified before writing them to disk

---

## Commands Practised
### `fdisk /dev/sdX`
Interactive tool for creating and managing MBR partitions.

### `gdisk /dev/sdX`
Interactive tool for creating and managing GPT partitions.

### `parted /dev/sdX`
Modern partitioning tool that supports both MBR and GPT, plus scripted partitioning.

---

## Reflection
Practising with `fdisk`, `gdisk`, and `parted` on the same disk device (in a safe test environment) made the differences between the tools very clear, rather than just theoretical.
