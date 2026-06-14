# Defensive Configurations

## Overview
This repository houses hardening guides, configuration files, and automation scripts designed to secure server environments and networks. The objective is to minimize attack surfaces and implement robust defense-in-depth strategies.

**Status**: Active Maintenance

## Included Categories
-   **Firewall Rules**: Templates for iptables, ufw, Windows Firewall, and pfSense.
-   **Server Hardening**: Secure baselines for Linux (Debian/Ubuntu/CentOS) and Windows Server.
-   **Intrusion Detection**: Snort, Suricata, and Sigma rule definitions for SIEM integration.
-   **Secure Baselines**: Docker container configurations and Kubernetes security policies.

## Principles
1.  **Zero Trust**: Assume the network is hostile; verify everything.
2.  **Least Privilege**: Grant only the minimum permissions necessary.
3.  **Defense in Depth**: Layer multiple security controls so failure of one does not compromise the whole.

## Usage
Reference the specific documentation files within subdirectories for your environment.
`git clone https://github.com/r4ttles/defensive-configs.git`

## Contributing
While contributors are welcome to suggest improvements via Issues, direct code merging requires explicit approval to maintain integrity.

## License Note
**Restricted Educational License applies.** View and personal use permitted. **No redistribution, resale, or forking allowed.** See `LICENSE.md` for full details.

---
*Last Updated: June 2026*
*Maintainer: r4ttles*
