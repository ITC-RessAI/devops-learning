# Switching Users

## Overview
**Switching Users** covers moving between accounts on the same system using `su`, either to become root or to switch to another user's session temporarily.

---

## Key Learnings
- `su` switches to another user, prompting for that user's password
- `su -` starts a full login shell with the target user's environment
- `su` differs from `sudo`: `su` starts a new session as another user, `sudo` runs a single command with elevated rights
- Exiting the switched session returns to the original user

---

## Commands Practised
### `su <username>`
Switches to another user account.

### `su -`
Switches to root with a full login environment.

### `exit`
Returns to the previous user's session.

---

## Reflection
Testing the difference between `su` and `sudo` side by side made the distinction between "becoming" a user and "borrowing" their privileges much clearer.
