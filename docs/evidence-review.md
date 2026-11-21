# Evidence review

Original files are retained privately, outside this repository. No screenshots were regenerated with AI. Selected video footage was shortened and its audio removed for publication.

| Original evidence | What it establishes | Publication decision |
| --- | --- | --- |
| 01-remote-lab-wake-on-lan-enabled.png | Adapter supports magic packets; disabled state changes to g | Commands/results transcribed; original contains MAC addresses and host identity |
| 02-wol-persistent-netplan-configuration.png | NetworkManager connections and initial Netplan inspection | Kept private; the filename alone does not prove persistence |
| 03-networkmanager-wake-on-lan-profile.png | Netplan reload warning, wakeonlan true, explicit NetworkManager magic setting | Relevant commands/results documented; original contains SSID and MAC values |
| 04-wol-settings-after-reboot.png | magic and Wake-on g after reboot | Results transcribed; full terminal screenshot retained privately |
| Pasted image.png | Tailscale installation and onboarding | Excluded: authentication URL and account details |
| Pasted image (2).png | First Ubuntu device in Tailscale | Excluded: authentication URL, account, address, and device details |
| 12.03.18 AM video | Earlier blank-screen problem | Troubleshooting described; not presented as a successful test |
| 12.15.36 AM video | Working laptop/desktop session | First 13 seconds published silently, plus a frame |
| 12.16.02 AM video | Additional connection footage | Retained privately |
| 12.40.22 AM ZIP | Two setup photos and three additional recordings | Reviewed representative frames/photos; retained privately because they show additional terminal and personal context |

The user confirmed local wake from suspend in the LABS conversation and later confirmed working desktop control, monitors, and sound in the portfolio conversation. Off-network power-on failed. The published footage alone does not establish hotspot connectivity, audio playback, or successful waking from full shutdown.

These text results are transcriptions, not substitutes presented as original screenshots:

```text
NetworkManager wake-on-lan profile: magic
Supports Wake-on: pumbg
Wake-on: g
```
