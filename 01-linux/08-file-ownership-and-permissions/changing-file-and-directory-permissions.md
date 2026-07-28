# Changing File & Directory Permissions

## Overview
**chmod** changes a file or directory's permissions, either using symbolic mode (`u+x`, `g-w`) or numeric/octal mode (`755`, `644`). Both approaches achieve the same result, but numeric mode is faster once the read/write/execute values are memorised.

---

## Key Learnings
- Symbolic mode uses `u` (user), `g` (group), `o` (others), with `+`/`-`/`=` to change permissions
- Numeric mode uses 3 digits, one per owner/group/other, each summing r=4, w=2, x=1
- `755` means owner has full access, group and others can read and execute only
- `chmod -R` applies changes recursively to a directory and its contents

---

## Commands Practised
### `chmod u+x file`
Adds execute permission for the file's owner.

### `chmod 644 file`
Sets read/write for the owner, read-only for group and others.

### `chmod -R 755 directory`
Recursively sets permissions on a directory and everything inside it.

---

## Reflection
Numeric mode felt confusing at first, but converting a few examples by hand (r+w+x = 4+2+1) made the math click quickly.
