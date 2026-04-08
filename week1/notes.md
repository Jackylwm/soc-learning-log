## Week 1 - Lab Setup and Windows Logging Basics
## Goals

- Set up the VM lab environment
- Learn to use Event Viewer
- Complete one TryHackMe room
- Write a self-introduction

## What I did

- Opened a GitHub repo
- Installed Ubuntu and Windows 11 on VirtualBox
- Joined the TryHackMe **Windows Event Logs** room to learn how to analyze logs in Windows

## What I learned

### Windows 11 minimum requirements

- **Processor:** 2 or more virtual processors (64-bit compatible)
- **Memory (RAM):** 4 GB or greater
- **Storage:** 64 GB or larger disk space
- **System firmware:** UEFI, Secure Boot capable
- **Security:** TPM 2.0 enabled
- **Graphics:** DirectX 12 compatible / WDDM 2.0

### VirtualBox troubleshooting

- If the Windows 11 VM shows a black screen, try **Reset**.

### Storage concepts

- **SATA** and **NVMe** are storage interfaces used to connect SSDs to a computer.

### Windows event log tooling

- Practiced retrieving and analyzing Windows Event Logs using:
    - **Get-WinEvent** (PowerShell)
    - **wevtutil** (command line)
- Reviewed common Windows Event Log fields and what they represent.

## Questions

## Next week

- Learn common Windows event IDs
- Set up Sysmon
