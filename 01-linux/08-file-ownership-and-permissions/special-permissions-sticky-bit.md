# Special Permissions – Sticky Bit

## Overview
The **sticky bit** applied to a directory restricts deletion — only the file's owner (or root) can delete or rename files inside it, even if others have write access to the directory. `/tmp` is the classic example.

---

## Key Learnings
- The sticky bit is applied at the directory level
- It prevents users from deleting files they don't own, even with directory write access
- Shown as a `t` in the "others" execute position in `ls -l`
- Commonly used on shared, world-writable directories like `/tmp`

---

## Commands Practised
### `chmod +t directory`
Sets the sticky bit on a directory.

### `chmod 1777 directory`
Sets the sticky bit using numeric mode (the leading `1`), alongside full read/write/execute for everyone.

---

## Reflection
Testing this against a shared directory with multiple test users showed exactly why `/tmp` needs the sticky bit — without it, anyone could delete anyone else's temp files.
