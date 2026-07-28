# Group File

## Overview
The **group file** (`/etc/group`) defines every group on the system and which users belong to it. Groups are how Linux manages shared access to files and resources across multiple users.

---

## Key Learnings
- `/etc/group` lists each group, its GID, and its members
- A user can belong to a primary group and multiple secondary groups
- Group membership controls shared file access without changing individual permissions
- GIDs work the same way UIDs do — numeric identifiers behind the group name

---

## Commands Practised
### `cat /etc/group`
Lists all groups and their members.

### `groups <user>`
Shows which groups a specific user belongs to.

---

## Reflection
Groups clicked once I saw them as a way to grant shared access without having to set individual permissions per user for every file.
