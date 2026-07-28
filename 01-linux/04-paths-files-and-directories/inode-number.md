# Inode Number

## Overview
An **inode** is the data structure Linux uses to store metadata about a file — everything except its name and its actual content. Every file has a unique **inode number**, which is how Linux actually identifies files internally; the filename is just a label pointing to that inode.

---

## Key Learnings
- Linux identifies files by inode number, not by filename
- An inode stores metadata: permissions, owner, size, timestamps, and pointers to data blocks
- Multiple filenames (hard links) can point to the same inode
- Running out of inodes can stop you from creating new files, even with free disk space

---

## Commands Practised
### `ls -i`
Displays the inode number next to each file.

### `stat`
Shows the inode number along with full file metadata.

---

## Reflection
Understanding inodes made hard links make sense immediately afterward — a hard link isn't a copy, it's just another name pointing at the same inode.
