# Managing Users

## Overview
**Managing Users** covers the full lifecycle of a user account: creating, modifying, and deleting accounts using `useradd`, `usermod`, and `userdel`.

---

## Key Learnings
- `useradd` creates a new user account
- `usermod` modifies an existing account, such as adding it to a group
- `userdel` removes a user account, optionally with their home directory
- Creating a user also affects `/etc/passwd`, `/etc/shadow`, and `/etc/group`

---

## Commands Practised
### `useradd <username>`
Creates a new user account.

### `usermod -aG <group> <username>`
Adds an existing user to an additional group.

### `userdel -r <username>`
Deletes a user account along with their home directory.

---

## Reflection
Creating and removing test users myself made it obvious how many system files get touched behind a single command like `useradd`.
