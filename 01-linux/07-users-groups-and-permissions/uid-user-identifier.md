# UID (User Identifier)

## Overview
Every user on a Linux system has a unique **UID**, which is what the system actually uses internally to identify them — usernames are just a human-friendly label mapped to a UID. Understanding UIDs explains how permissions and ownership are tracked at a lower level than usernames.

---

## Key Learnings
- Every user account has a numeric UID, unique on that system
- UID 0 is always reserved for the root user
- Regular users are typically assigned UIDs starting from 1000
- File ownership is actually stored by UID, with the username resolved for display

---

## Commands Practised
### `id`
Displays the current user's UID, GID, and group memberships.

### `whoami`
Displays the current logged-in username.

### `cat /etc/passwd`
Lists all users on the system along with their UID and other account details.

---

## Reflection
Seeing that ownership is really tracked by number, not by name, changed how I think about permissions — a username is just a label on top of the UID.
