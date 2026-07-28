# Disk Partitioning

## Overview
**Disk Partitioning** divides a single physical disk into separate, independently managed sections. Each partition can have its own file system and be mounted independently, which is useful for organizing storage or isolating data.

---

## Key Learnings
- A disk can be divided into multiple partitions, each acting as an independent storage unit
- Partition tables come in two main types: MBR (older) and GPT (modern, supports larger disks)
- Each partition needs its own file system before it can be mounted
- Partitioning tools differ (`fdisk` for MBR, `gdisk`/`parted` for GPT)

---

## Reflection
Understanding the MBR vs GPT distinction before jumping into partitioning tools saved me a lot of confusion once I started using `fdisk` and `parted` hands-on.
