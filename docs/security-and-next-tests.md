# Security boundaries and follow-up work

## Completed functional scope

The owner verified cellular-hotspot access to the HP relay through Tailscale/OpenSSH, local magic-packet wake of the desktop from suspend, and a successful NoMachine session. No router port-forward was added for this lab. This does not establish that all services are unreachable from other interfaces or that unrelated router mappings do not exist.

## Implemented choices

- Private Tailscale connectivity for the remote access path.
- Separate Ubuntu account authentication for SSH and NoMachine.
- SSH host fingerprint checked against the physical relay console.
- Updates installed; the relay subsequently reported no pending updates at that checkpoint.
- Lid handling configured for operation on external power.
- Public evidence redacted; original screenshots kept outside the repository.

## Not yet implemented or verified

- SSH public-key login and disabling password authentication. Test key login in a second session before changing password access.
- Identity-provider MFA review, authorized-device review and least-privilege Tailscale rules.
- Host firewall/interface reachability review and router mapping review.
- Ongoing patch policy, prolonged uptime and failure recovery.
- NoMachine licensing after the evaluation period.
- Explanation of the anomalous ACPI temperature sensor. CPU readings were much lower; no hardware-health certification is claimed.

## Optional reliability tests

| Test | Current state |
| --- | --- |
| Wake from suspend over cellular | Passed |
| Relay reboot then LAN SSH recovery | Passed |
| Saved lid policy and SSH during lid-test workflow | Recorded; physical lid state is not visible in screenshot |
| Full shutdown wake | Untested; depends on firmware/NIC/power configuration |
| Recovery after power or router outage | Untested |
| Long-duration closed-lid operation | Untested |
| Lock/reconnect and VM operation in final hotspot run | Not separately documented |

Tailscale encryption does not protect an already-compromised authorized endpoint or eliminate the need to secure the sign-in account. Wake-on-LAN packets are not a substitute for login authentication. The relay was not configured as an internet router, subnet router or exit node.

## Publication review

Opaque masks cover authentication URLs, account emails, LAN/Tailscale/public IP addresses, MACs, SSIDs, serials and device UUIDs where visible. Public author name, generic host labels, interface names and technical results are retained. PNG copies were flattened and metadata removed. Redacting an address is a privacy measure, not a security control. No private keys, passwords or license keys are intentionally published. No claim of an attack simulation or security audit is made.
