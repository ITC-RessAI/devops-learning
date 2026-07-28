# YUM

## Overview
**YUM** is a higher-level package manager built on top of RPM that automatically resolves and installs dependencies from configured repositories, making software installation far less manual.

---

## Key Learnings
- YUM automatically resolves and installs dependencies
- Packages are pulled from configured repositories, not just local files
- YUM can update, search, and remove packages, in addition to installing them
- Repository configuration lives under `/etc/yum.repos.d/`

---

## Commands Practised
### `yum install package`
Installs a package and its dependencies from a configured repository.

### `yum update`
Updates all installed packages to their latest available versions.

### `yum remove package`
Removes an installed package.

### `yum search keyword`
Searches available repositories for packages matching a keyword.

---

## Reflection
Going from RPM straight to YUM made the dependency-resolution benefit immediate — no more manually chasing down missing packages one error at a time.
