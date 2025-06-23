# Blocklist Configuration for Auto-Provisioning

This file defines domains to be blocked and is automatically fetched every 24 hours by the system that manages internet restrictions in Laboratories 1–6.

## ⚠️ Critical Notice

- **Each line must contain exactly one domain** (e.g., `example.com`). Wildcards (e.g., `*.example.com`) are supported.
- **Incorrect entries can cause partial or complete internet outages** in the labs. Double-check all changes.
- There are already rules in place blocking **adware, malware, NSFW content**, and other known threats.
  **DO NOT use this file for that purpose!**
- To safely propose updates:
  1. **Create a new branch**.
  2. **Open a Pull Request (PR)**.
  3. **Request a code review** before merging into the main branch.