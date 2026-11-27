# Portfolio handoff

## Project

**Secure Remote Access & Wake-on-LAN Home Lab** — Freddy Flores, November 2026.

**Status:** Core functional goal complete; optional hardening and resilience work remains.

## Suggested summary

Built and tested remote access to a home Ubuntu desktop using Tailscale, NoMachine and a repurposed HP Ubuntu Server laptop as a Wake-on-LAN relay. Verified the full workflow from a Windows laptop on an iPhone cellular hotspot: SSH to the relay, wake the wired desktop from suspend, then connect to the existing desktop session. Documented installation, persistent wake settings, lid behavior, troubleshooting and security limitations.

## Skills demonstrated

Linux installation and administration; SSH host verification; private networking; Ethernet Wake-on-LAN; NetworkManager/Netplan; systemd power behavior; remote desktop troubleshooting; evidence handling and honest test reporting.

## Assets and links

- Main case study: `README.md`
- Architecture: `assets/connection-map.svg`
- Cover: `assets/thumbnail.svg`
- Final outcome: `assets/evidence/18-hotspot-remote-desktop-success.png`
- Complete 18-image gallery: `docs/evidence-review.md`
- Reproduction: `docs/configuration-walkthrough.md`
- Limitations: `docs/security-and-next-tests.md`

Use repository-relative paths or resolve them against the repository when importing. Use only published redacted images. Do not claim shutdown wake, key-only SSH, audited firewall rules, verified MFA, production hardening or a router deployment. The final photograph supports the desktop session; the cellular/wake sequence is owner-confirmed. Existing video is earlier session footage, not a recording of the final hotspot test.
