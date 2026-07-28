# Managing Groups

## Overview
**Managing Groups** covers creating, modifying, and deleting groups, and managing which users belong to them, using `groupadd`, `groupmod`, and `gpasswd`.

---

## Key Learnings
- `groupadd` creates a new group
- `groupmod` renames or modifies an existing group
- `gpasswd` manages group membership and group passwords
- Groups make it possible to grant shared file access to multiple users at once

---

## Commands Practised
### `groupadd <groupname>`
Creates a new group.

### `groupmod -n <newname> <oldname>`
Renames an existing group.

### `gpasswd -a <user> <group>`
Adds a user to a group.

---

## Reflection
Managing groups alongside users made the bigger picture click: permissions in Linux are as much about groups as they are about individual users.
