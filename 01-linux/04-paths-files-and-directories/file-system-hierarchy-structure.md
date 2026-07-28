# File System Hierarchy Structure

## Overview
The **File System Hierarchy Structure (FHS)** defines the standard layout of directories in Linux. Everything starts from a single root directory `/`, with well-defined subdirectories for configuration (`/etc`), user files (`/home`), variable data (`/var`), and installed programs (`/usr`).

Knowing this layout means I can predict where things live on almost any Linux system, instead of guessing.

---

## Key Learnings
- Linux uses a single unified tree starting at `/`, unlike Windows' drive letters
- `/etc` holds system configuration files
- `/home` holds user data and personal files
- `/var` holds variable data such as logs
- `/usr` holds installed software and shared resources

---

## Commands Practised
### `ls /`
Lists the top-level directories of the file system to explore the hierarchy directly.

### `tree` (or `ls -R`)
Displays a directory's structure recursively, useful for visualising the hierarchy.

---

## Reflection
Once the FHS clicked, navigating any Linux system — even one I'd never seen before — became far less intimidating, because I knew roughly where to look.
