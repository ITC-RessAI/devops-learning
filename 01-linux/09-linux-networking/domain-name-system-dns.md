# Domain Name System (DNS)

## Overview
**DNS** resolves human-readable hostnames (like `example.com`) into IP addresses that machines actually use to communicate. Understanding DNS resolution is essential for troubleshooting connectivity issues that look like "the internet is down" but are really name-resolution problems.

---

## Key Learnings
- DNS translates domain names into IP addresses
- Linux checks `/etc/resolv.conf` (or a system resolver) for DNS server configuration
- `/etc/hosts` allows manual, local hostname-to-IP mappings that bypass DNS
- DNS issues can look like general connectivity issues but are actually resolution failures

---

## Commands Practised
### `nslookup <domain>`
Queries DNS to resolve a domain name to an IP address.

### `dig <domain>`
Provides a more detailed DNS query and response than `nslookup`.

### `cat /etc/resolv.conf`
Views the DNS servers currently configured for the system.

---

## Reflection
Testing DNS resolution directly with `dig` made me realise how much of "the internet not working" is actually a name-resolution problem, not a connectivity one.
