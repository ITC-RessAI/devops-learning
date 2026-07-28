# Shadow File

## Overview
The **shadow file** (`/etc/shadow`) stores hashed user passwords and password policy details, separate from `/etc/passwd`. Keeping password hashes in a file only root can read is a core Linux security practice.

---

## Key Learnings
- `/etc/shadow` stores hashed passwords, not plaintext
- Only the root user can read `/etc/shadow` by default
- It also stores password expiry and ageing policy fields
- Separating it from `/etc/passwd` (which is world-readable) protects password hashes from exposure

---

## Commands Practised
### `sudo cat /etc/shadow`
Views the shadow file's contents (requires root privileges).

### `chage -l <user>`
Displays password ageing information for a user.

---

## Reflection
Comparing `/etc/passwd` and `/etc/shadow` side by side made it clear why Linux splits account info from password hashes — it's a deliberate security boundary.
