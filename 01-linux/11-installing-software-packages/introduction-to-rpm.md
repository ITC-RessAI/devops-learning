# Introduction to RPM

## Overview
**RPM (Red Hat Package Manager)** is the low-level package manager used on RHEL-based distributions. It installs, queries, verifies, and removes individual `.rpm` package files, but it doesn't resolve dependencies automatically — that's what YUM handles on top of it.

---

## Key Learnings
- RPM works directly with individual `.rpm` package files
- It does not resolve or download dependencies automatically
- RPM can query installed packages and verify their integrity
- RPM is the foundation that higher-level tools like YUM are built on

---

## Commands Practised
### `rpm -ivh package.rpm`
Installs a package from a local `.rpm` file, showing progress and hash marks.

### `rpm -qa`
Lists all installed RPM packages.

### `rpm -e package`
Removes an installed package.

---

## Reflection
Installing a package with plain RPM and hitting a dependency error firsthand made it obvious why YUM exists on top of it.
