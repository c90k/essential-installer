# Essential Installer

A unified, automated Windows runtime installer designed to deploy all standard prerequisites for modern software and PC gaming in a single pass.

---

## Overview

Setting up a fresh Windows installation or troubleshooting missing runtime errors (`MSVCP*.dll`, missing DirectX extensions, or .NET framework dependencies) often requires locating and running multiple separate setup files. 

**Essential Installer** packages all required packages together with silent/automated switches to set up your environment cleanly without manual intervention.

---

## Included Components

| Runtime | Architectures | Versions Included |
| :--- | :--- | :--- |
| **Visual C++ Redistributables** | x86, x64 | 2005, 2008, 2010, 2012, 2013, 2015–2022 (Combined) |
| **DirectX End-User Runtimes** | x86, x64 | June 2010 Redistributable (DirectX 9.0c, 10, 11 components) |
| **Microsoft .NET Desktop Runtime** | x64 | 6.0 LTS, 7.0, 8.0 LTS, 9.0 |
| **Microsoft .NET Framework** | System-wide | 3.5 (includes 2.0 & 3.0), 4.8.1 |

---

## Requirements

- **Operating System:** Windows 10 (1809+) or Windows 11
- **Privileges:** Administrator access (required to write system libraries and invoke Microsoft installers)
- **Disk Space:** ~2.5 GB temporary space during extraction and deployment

---

## Installation

1. Go to the **[Releases](../../releases/latest)** section.
2. Download the latest `Essential-Installer-vX.X.X.zip`
3. Extract the contents if downloaded as an archive.
4. Right-click the installer executable and choose **Run as administrator**.
5. Follow the on-screen prompts (or let it complete automatically if running in silent mode).
