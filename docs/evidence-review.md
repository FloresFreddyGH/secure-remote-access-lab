# Evidence gallery and review

All **18 PNG files** present in the owner’s Remote Desktop Lab folder were reviewed and included below as public derivatives. Originals remain unchanged outside Git. Filenames were normalized for publication, including one original containing a newline. Opaque pixel masks remove sensitive values; larger photos were resized to at most 1500 pixels per dimension and all PNG metadata was removed. No AI reconstruction, invented output or changes to test results were used.

The final cellular wake and NoMachine outcome is explicitly owner-confirmed on November 27, 2026. Screenshots establish only the visible states described in their captions. A filename is not treated as proof of a result. Exact timings, full-shutdown wake and security hardening are not established.

## Source mapping

| # | Original local filename | Public copy |
| --- | --- | --- |
| 01 | `01-remote-lab-wake-on-lan-enabled.png` | [01-wol-enabled.png](../assets/evidence/01-wol-enabled.png) |
| 02 | `02-wol-persistent-netplan-configuration.png` | [02-network-configuration.png](../assets/evidence/02-network-configuration.png) |
| 03 | `03-networkmanager-wake-on-lan-profile.png` | [03-wol-persistence.png](../assets/evidence/03-wol-persistence.png) |
| 04 | `04-wol-settings-after-reboot.png` | [04-wol-after-reboot.png](../assets/evidence/04-wol-after-reboot.png) |
| 05 | `CONNECTED.png` | [05-relay-tailscale-connected.png](../assets/evidence/05-relay-tailscale-connected.png) |
| 06 | `Pasted image (2).png` | [06-desktop-tailscale-device.png](../assets/evidence/06-desktop-tailscale-device.png) |
| 07 | `Pasted image (3).png` | [07-relay-storage-summary.png](../assets/evidence/07-relay-storage-summary.png) |
| 08 | `Pasted image (4).png` | [08-relay-lid-configuration.png](../assets/evidence/08-relay-lid-configuration.png) |
| 09 | `Pasted image.png` | [09-desktop-tailscale-onboarding.png](../assets/evidence/09-desktop-tailscale-onboarding.png) |
| 10 | `home-wake-relay-hardware-inventory.png` | [10-relay-hardware.png](../assets/evidence/10-relay-hardware.png) |
| 11 | `home-wake-relay-lid-closed-ssh-test.png` | [11-relay-reboot-ssh.png](../assets/evidence/11-relay-reboot-ssh.png) |
| 12 | `home-wake-relay-ssh-installation-settings.png` | [12-relay-ssh-installer.png](../assets/evidence/12-relay-ssh-installer.png) |
| 13 | `home-wake-relay-ssh-over-tailscale.png` | [13-windows-relay-ssh.png](../assets/evidence/13-windows-relay-ssh.png) |
| 14 | `home-wake-relay-storage-layout.png` | [14-relay-wifi-connected.png](../assets/evidence/14-relay-wifi-connected.png) |
| 15 | `home-wake-relay-ubuntu-installation-complete\n1..png` | [15-relay-installation-complete.png](../assets/evidence/15-relay-installation-complete.png) |
| 16 | `home-wake-relay-ubuntu-server-usb-ready.png` | [16-server-usb-ready.png](../assets/evidence/16-server-usb-ready.png) |
| 17 | `home-wake-relay-wifi-connected.png` | [17-installer-language.png](../assets/evidence/17-installer-language.png) |
| 18 | `remote-desktop-hotspot-end-to-end-success.png` | [18-hotspot-remote-desktop-success.png](../assets/evidence/18-hotspot-remote-desktop-success.png) |

## Screenshots

### 01. Wol enabled

Adapter support and change from disabled wake to magic-packet wake. MAC addresses covered.

![Adapter support and change from disabled wake to magic-packet wake. MAC addresses covered.](../assets/evidence/01-wol-enabled.png)

### 02. Network configuration

Network and Netplan inspection before persistence was configured. MACs and Wi-Fi name covered.

![Network and Netplan inspection before persistence was configured. MACs and Wi-Fi name covered.](../assets/evidence/02-network-configuration.png)

### 03. Wol persistence

Netplan warning, explicit NetworkManager magic setting and adapter check. MACs and Wi-Fi name covered.

![Netplan warning, explicit NetworkManager magic setting and adapter check. MACs and Wi-Fi name covered.](../assets/evidence/03-wol-persistence.png)

### 04. Wol after reboot

Post-reboot checks return magic and Wake-on: g. No sensitive values requiring masks identified.

![Post-reboot checks return magic and Wake-on: g. No sensitive values requiring masks identified.](../assets/evidence/04-wol-after-reboot.png)

### 05. Relay tailscale connected

Relay Tailscale installation and successful enrollment. Authentication URL, account identifiers and addresses covered.

![Relay Tailscale installation and successful enrollment. Authentication URL, account identifiers and addresses covered.](../assets/evidence/05-relay-tailscale-connected.png)

### 06. Desktop tailscale device

Desktop listed in Tailscale administration. Authentication URL, email, address and unrelated browser context covered.

![Desktop listed in Tailscale administration. Authentication URL, email, address and unrelated browser context covered.](../assets/evidence/06-desktop-tailscale-device.png)

### 07. Relay storage summary

Actual storage summary: root LVM, boot and EFI partitions. Device serial strings and background card covered.

![Actual storage summary: root LVM, boot and EFI partitions. Device serial strings and background card covered.](../assets/evidence/07-relay-storage-summary.png)

### 08. Relay lid configuration

Lid-policy file created after the initial missing-file error; contents verified. Network addresses covered.

![Lid-policy file created after the initial missing-file error; contents verified. Network addresses covered.](../assets/evidence/08-relay-lid-configuration.png)

### 09. Desktop tailscale onboarding

Desktop Tailscale onboarding. Authentication URL, email and unrelated browser context covered.

![Desktop Tailscale onboarding. Authentication URL, email and unrelated browser context covered.](../assets/evidence/09-desktop-tailscale-onboarding.png)

### 10. Relay hardware

HP model, processor and memory inventory. Rotated for reading; serial, UUID and service identifiers covered.

![HP model, processor and memory inventory. Rotated for reading; serial, UUID and service identifiers covered.](../assets/evidence/10-relay-hardware.png)

### 11. Relay reboot ssh

Relay reboot, SSH reconnection, hostname and uptime during the lid-test workflow. Addresses covered; lid position is not visible.

![Relay reboot, SSH reconnection, hostname and uptime during the lid-test workflow. Addresses covered; lid position is not visible.](../assets/evidence/11-relay-reboot-ssh.png)

### 12. Relay ssh installer

SSH installer screen BEFORE OpenSSH was selected. It does not prove installation; subsequent working SSH does.

![SSH installer screen BEFORE OpenSSH was selected. It does not prove installation; subsequent working SSH does.](../assets/evidence/12-relay-ssh-installer.png)

### 13. Windows relay ssh

Windows SSH session to the relay and hostname check. Addresses covered. Cellular transport is owner-confirmed, not visible here.

![Windows SSH session to the relay and hostname check. Addresses covered. Cellular transport is owner-confirmed, not visible here.](../assets/evidence/13-windows-relay-ssh.png)

### 14. Relay wifi connected

Actual Wi-Fi connection screen: DHCP configuration and Ethernet disconnected. Addresses, SSID and background card covered.

![Actual Wi-Fi connection screen: DHCP configuration and Ethernet disconnected. Addresses, SSID and background card covered.](../assets/evidence/14-relay-wifi-connected.png)

### 15. Relay installation complete

Ubuntu Server installation complete. No sensitive values requiring masks identified.

![Ubuntu Server installation complete. No sensitive values requiring masks identified.](../assets/evidence/15-relay-installation-complete.png)

### 16. Server usb ready

Ubuntu Server USB image written in Disks. Serial, volume identifier and personal mount path covered.

![Ubuntu Server USB image written in Disks. Serial, volume identifier and personal mount path covered.](../assets/evidence/16-server-usb-ready.png)

### 17. Installer language

Actual installer language-selection screen, despite the original Wi-Fi filename. Background card covered.

![Actual installer language-selection screen, despite the original Wi-Fi filename. Background card covered.](../assets/evidence/17-installer-language.png)

### 18. Hotspot remote desktop success

Final NoMachine session after owner-confirmed cellular hotspot wake test. Terminal address/key context covered. The photo alone does not prove previous sleep state or network transport.

![Final NoMachine session after owner-confirmed cellular hotspot wake test. Terminal address/key context covered. The photo alone does not prove previous sleep state or network transport.](../assets/evidence/18-hotspot-remote-desktop-success.png)

## Earlier published media

The existing remote-session photos and silent demonstration clip show earlier desktop control, not the final hotspot test. Earlier blank-screen recordings and extra raw footage remain private. Audio and multi-monitor functionality were owner-confirmed in earlier testing, not inferred from the silent clip.

## Integrity

`evidence-manifest.json` lists SHA-256 hashes of the public derivatives for integrity checks. Redactions are flattened pixels, not removable overlays. These files still expose intended technical context such as OS versions and interface names; hiding all technical information would defeat the purpose of the lab evidence.
