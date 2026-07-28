# Key-pair Authentication

## Overview
**Key-pair authentication** replaces password-based SSH login with a public/private key pair — far more secure and the standard approach for accessing cloud servers like AWS EC2 instances.

---

## Key Learnings
- A key pair consists of a private key (kept secret, stays on your machine) and a public key (placed on the server)
- The server never sees the private key — only proof that you hold it
- Key-based authentication is generally more secure than passwords, and is required by default on most cloud providers
- Private keys should always have restricted file permissions (`600`)

---

## Commands Practised
### `ssh-keygen`
Generates a new public/private SSH key pair.

### `ssh -i <keyfile> user@host`
Connects to a remote system using a specific private key.

### `chmod 600 <keyfile>`
Restricts a private key file's permissions so only the owner can read it.

---

## Reflection
Generating my own key pair and using it to connect to an EC2 instance made key-based auth click far faster than reading about it — and explained why AWS enforces it by default.
