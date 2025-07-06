# Internet Access Control Configuration for Auto-Provisioning

This repository contains configuration files that define internet access restrictions and are automatically fetched every 6 hours by the system that manages internet access in Laboratories 1–6.

## Files

- **`blocklist.txt`**: Domains to be blocked
- **`allowlist.txt`**: Domains that are explicitly allowed and will bypass certain restrictions

## Transparency Notice

This repository is **publicly accessible** to ensure transparency in our internet access policies. All changes are visible and can be tracked through the commit history.

## Critical Notice

- **Each line must contain exactly one domain** (e.g., `example.com`). Wildcards (e.g., `*.example.com`) are supported.
- **Incorrect entries can cause partial or complete internet outages** in the labs. Double-check all changes.
- The **`allowlist.txt`** contains essential domains required for core university services (Microsoft Office, university systems, etc.). Removing entries from this file may break critical functionality.
- There are already rules in place blocking **adware, malware, NSFW content**, and other known threats.
  **DO NOT use the blocklist for that purpose!**
- To safely propose updates:
  1. **Create a new branch**.
  2. **Open a Pull Request (PR)**.
  3. **Request a code review** before merging into the main branch.