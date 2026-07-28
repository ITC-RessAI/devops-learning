# Disk Management Concepts

## Overview
**Disk Management Concepts** covers how Linux represents physical and virtual storage devices, and the general workflow for making a disk usable: partitioning, formatting with a file system, then mounting it into the directory tree.

---

## Key Learnings
- Disks are represented as device files under `/dev` (e.g. `/dev/sda`)
- The typical workflow is: partition → format → mount
- A raw disk isn't usable until it has a file system and is mounted
- Linux can manage multiple physical and virtual disks simultaneously

---

## Reflection
Seeing the full path from raw disk to usable storage — partition, format, mount — tied the rest of this module's commands into one coherent process.
