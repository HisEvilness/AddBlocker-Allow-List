# AddBlocker-Allow-List

Unified DNS Allowlist

A centralized allowlist repository designed to resolve false positives caused by aggressive DNS filtering configurations. Optimized for AdGuard Home, Pi-hole, NextDNS, and broader DNS-based security appliances that require controlled access restoration to legitimate services.

Allowlist Structure
List	Description	Raw URL

--- Core Allowlist	Primary allowlist restoring functionality for widely-used services incorrectly blocked by privacy filters. Safe for all deployments.	https://raw.githubusercontent.com/<username>/<repo>/main/allow-core.txt
--- Extended Allowlist	Optional allowlist for advanced users. Includes additional platforms, infrastructure services, CDNs, gaming, media, and communication endpoints.	https://raw.githubusercontent.com/<username>/<repo>/main/allow-extended.txt

Start with Core. Add Extended only when needed to fix functionality issues.

Disclaimer

This allowlist is intended solely for enabling access to legitimate online resources. Use responsibly within your organization’s threat and compliance boundaries.
