# VPN Setup Report (Windows)

Name: Siddharth Kaushik
Date: 2025-10-04
VPN provider chosen: ProtonVPN Free
Windows version: Windows 11 Home

## Steps performed
1. Installed ProtonVPN client from official site.
2. Public IP before: 103.87.xx.xx
   ![IP Before Screenshot](/screenshots/IP-Before.png).
3. Connected to VPN (server: Netherlands).
   ![Connection Status Screenshot](/screenshots/Connect2.png).
4. Public IP after: 149.34.xx.xx
   ![IP After Screenshot](/screenshots/IP-After.png).
5. Speed test before/after:
   ![Speed Test Before Screenshot](/screenshots/Speed-Before.png) ![Speed Test After Screenshot](/screenshots/Speed-After.png).

## Observations
- IP change confirmed: Yes
- Speed before: 54.75 Mbps download / 83.40 Mbps upload
- Speed after: 45.31 Mbps download / 61.10 Mbps upload
- Notes: Connection stable, minor speed drop noticed.

## Short summary
- Benefits: Public IP hidden, traffic encrypted, safer on public WiFi.
- Limitations: Free servers crowded at peak times, slight speed drop.

## Files included
- `screenshots/*`
- `scripts/check_ip.ps1`
