# Security and remaining tests

## Implemented approach

Remote desktop is reached using Tailscale and an Ubuntu system login. No router port-forward was added as part of this lab. Public documentation excludes raw authentication URLs, license keys, account details, MAC addresses and home network identifiers. Redaction does not itself secure a service; account and network controls still matter.

## Controls to verify next (not claimed complete)

- Review identity-provider MFA, authorized Tailscale devices and least-privilege access rules.
- Confirm the host firewall limits remote-desktop reachability to intended networks/devices; check for any unrelated router forwards or automatic mappings.
- Keep both operating systems, Tailscale and NoMachine updated.
- Configure the home relay with restricted remote access and only the permissions needed to send the wake packet.
- Keep raw screenshots and logs private. Remove any exposed reusable credentials before sharing further evidence.
- Decide how to license NoMachine after the evaluation period.

## Acceptance test for the next milestone

1. Power the spare home laptop and keep it awake; configure it as the wake relay.
2. Connect the Windows client to a phone hotspot using cellular data.
3. Reach the relay through Tailscale and send the local wake packet.
4. Confirm Ubuntu resumes, Tailscale reconnects and NoMachine displays the desktop.
5. Verify both displays, audio, lock/reconnect and lab VM access.
6. Repeat from full shutdown separately; record any firmware dependency.
7. Record timings, failures and recovery steps rather than assuming every case works.

No attack simulation, security audit, MFA verification, or firewall hardening is claimed by the current demonstration.
