# File Ownership

## Overview
**chown** and **chgrp** change which user and group own a file. Ownership determines whose permission set applies when the "owner" and "group" categories are evaluated.

---

## Key Learnings
- `chown` changes a file's owning user (and optionally its group)
- `chgrp` changes only a file's owning group
- Only root (or the current owner, in limited cases) can change ownership
- Ownership and permissions work together — permissions decide *what*, ownership decides *who*

---

## Commands Practised
### `chown user file`
Changes a file's owner.

### `chown user:group file`
Changes both owner and group in one command.

### `chgrp group file`
Changes only a file's owning group.

---

## Reflection
Practising `chown` on files created by different test users made the connection between UID/GID and permissions much more concrete.
