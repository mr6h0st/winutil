# Windows 10/11 Utility - tweaked by 6h0st
# original project by Chris Titus Tech

This Utility is a compilation of windows tasks I perform on each Windows system I use. It is meant to streamline *installs*, debloat with *tweaks*, troubleshoot with *config*, and fix Windows *updates*. I am extremely picky on any contributions to keep this project clean and efficient. 

![screen-install](screen-install.png)

Requires you to launch PowerShell or Windows Terminal As ADMINISTRATOR! 

The recommended way is to right click on the start menu and select (PowerShell As Admin *Windows 10* - Windows Terminal As Admin *Windows 11*)

Launch Command:

```
iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/mr6h0st/winutil/main/winutil.ps1'))
```
If you are having TLS 1.2 issues, then run with the following command:
```
[Net.ServicePointManager]::SecurityProtocol=[Net.SecurityProtocolType]::Tls12;iex(New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/mr6h0st/winutil/main/winutil.ps1')
```

## Overview

- Install
  - Installs all selected programs
  - Has Upgrade ALL existing programs button
- Tweaks
  - Optimizes windows and reduces running processes
  - Has recommended settings for each type of system
- Config
  - Quick configurations for Windows Installs
  - Has old legacy panels from Windows 7
  - Reset Windows Update to factory settings
  - System Corruption Scan
- Updates
  - Fixes the default windows update scheme
