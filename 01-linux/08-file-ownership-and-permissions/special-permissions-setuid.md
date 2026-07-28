# Special Permissions – Setuid

## Overview
**Setuid** (Set User ID) is a special permission that lets an executable run with the privileges of its *owner*, rather than the user who launched it. It's commonly used for programs that need elevated access for a specific task, like `passwd`.

---

## Key Learnings
- Setuid only applies to executable files
- When set, the program runs as its owner (often root), not the invoking user
- Shown as an `s` in place of the owner's execute bit in `ls -l`
- Misused setuid binaries are a common security risk, so they should be used sparingly

---

## Commands Practised
### `chmod u+s file`
Sets the setuid bit on an executable.

### `chmod 4755 file`
Sets setuid using numeric mode (the leading `4`).

### `ls -l`
Confirms the setuid bit by checking for an `s` in the owner's permission field.

---

## Reflection
Testing setuid on a small script and watching it run with elevated privileges made a permission that sounded abstract feel very concrete.
