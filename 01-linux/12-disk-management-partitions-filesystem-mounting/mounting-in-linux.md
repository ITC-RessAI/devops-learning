# Mounting in Linux

## Overview
**Mounting** attaches a formatted partition's file system to a specific point in the Linux directory tree, making its contents accessible. Until it's mounted, a partition's data isn't reachable through the file system at all.

---

## Key Learnings
- Mounting attaches a partition to a directory (the "mount point")
- `mount` mounts a partition temporarily, until reboot
- `/etc/fstab` defines partitions that should mount automatically at boot
- `umount` safely detaches a mounted partition

---

## Commands Practised
### `mount /dev/sdX1 /mnt/data`
Mounts a partition to a specified mount point.

### `umount /mnt/data`
Unmounts a previously mounted partition.

### `cat /etc/fstab`
Views the configuration for partitions that mount automatically at boot.

---

## Reflection
Editing `/etc/fstab` and testing that a partition survived a reboot tied the whole disk-management module together into something that actually persists.
