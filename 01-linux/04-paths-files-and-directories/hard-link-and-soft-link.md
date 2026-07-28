# Hard Link and Soft Link

## Overview
A **hard link** is an additional filename pointing to the exact same inode as the original file — they're indistinguishable from Linux's point of view. A **soft link** (symbolic link) is a separate file that simply points to another file's path, similar to a shortcut.

---

## Key Learnings
- Hard links share the same inode as the original file
- Deleting the original file doesn't affect a hard link, since the data stays until all links are removed
- Soft links point to a path, not an inode, so they break if the target is deleted or moved
- Soft links can cross file systems; hard links generally cannot

---

## Commands Practised
### `ln`
Creates a hard link between an existing file and a new filename.

### `ln -s`
Creates a symbolic (soft) link pointing to a target path.

### `ls -li`
Lists files with inode numbers, useful for confirming hard links share the same inode.

---

## Reflection
Testing this hands-on — deleting the original file and watching what happened to each link type — made the difference between hard and soft links far clearer than just reading about it.
