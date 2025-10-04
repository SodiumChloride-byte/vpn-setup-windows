# working-with-vpns (Windows)

Objective  
- Install a free VPN client on Windows, connect, verify IP change, run speed tests, and submit a report with screenshots.

What to include  
- `screenshots/` — before/after IP, VPN connection status, speed tests.  
- `REPORT_TEMPLATE.md` — write your report here or export to PDF.  
- `scripts/check_ip.ps1` — PowerShell script to capture your public IP.  

Steps  
1. Choose a VPN [Proton VPN](https://protonvpn.com/download-windows), [Windscribe VPN](https://windscribe.com/features/windows/). (I preffered Proton VPN). 
2. Install the Windows client (see INSTALL.md).  
3. Before connecting, run `scripts/check_ip.ps1` and screenshot output (`ip-before.png`).  
4. Connect the VPN. Screenshot app showing “Connected” (`connection-status.png`).  
5. Run `scripts/check_ip.ps1` again, screenshot output (`ip-after.png`).  
6. Run an internet speed test before and after using [Ookla Speedtest](https://www.speedtest.net/apps/windows) or [Fast.com](https://fast.com). Save screenshots as `speed-before.png` and `speed-after.png`.  
7. Full Report [REPORT.md](./REPORT.md)  
