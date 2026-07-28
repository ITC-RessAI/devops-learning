# Special Permissions – Setgid

## Overview
**Setgid** (Set Group ID) works like setuid but for groups. On an executable, it runs with the file's group privileges; on a directory, it makes new files created inside automatically inherit the directory's group.

---

## Key Learnings
- On executables, setgid runs the program with the file's group privileges
- On directories, setgid makes new files inherit the directory's group automatically
- Shown as an `s` in the group execute position in `ls -l`
- Commonly used on shared directories where multiple users need consistent group ownership

---

## Commands Practised
### `chmod g+s directory`
Sets the setgid bit on a directory.

### `chmod 2755 directory`
Sets setgid using numeric mode (the leading `2`).

---

## Reflection
Setting setgid on a shared test directory and watching new files inherit the group automatically made this one of the more genuinely useful permissions I practised.
