# VPN Setup Report (Windows)

Name: John Doe
Date: 2025-10-04
VPN provider chosen: ProtonVPN Free
Windows version: Windows 11 Home

## Steps performed
1. Installed ProtonVPN client from official site.
2. Public IP before: 203.0.113.45 (screenshot `ip-before.png`).
3. Connected to VPN (server: Netherlands). (screenshot `connection-status.png`).
4. Public IP after: 185.159.158.12 (screenshot `ip-after.png`).
5. Speed test before/after: (screenshots `speed-before.png` / `speed-after.png`).

## Observations
- IP change confirmed: Yes
- Speed before: 95 Mbps download / 25 Mbps upload
- Speed after: 72 Mbps download / 18 Mbps upload
- Notes: Connection stable, minor speed drop noticed.

## Short summary
- Benefits: Public IP hidden, traffic encrypted, safer on public WiFi.
- Limitations: Free servers crowded at peak times, slight speed drop.

## Files included
- `screenshots/*`
- `scripts/check_ip.ps1`
