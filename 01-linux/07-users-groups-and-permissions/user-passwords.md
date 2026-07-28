# User Passwords

## Overview
**User Passwords** covers setting and managing account passwords, along with password ageing policy — how often a password must be changed and how long it stays valid.

---

## Key Learnings
- `passwd` sets or changes a user's password
- Root can set another user's password directly; regular users can only change their own
- Password ageing policy controls expiry, warning periods, and minimum change intervals
- Password data is stored, hashed, in `/etc/shadow`

---

## Commands Practised
### `passwd`
Changes the current user's password.

### `passwd <username>`
Sets another user's password (requires root).

### `chage`
Views or sets password ageing policy for a user.

---

## Reflection
Working with `chage` showed me password management is more than just setting a password once — expiry and ageing policy matter for real system security.
