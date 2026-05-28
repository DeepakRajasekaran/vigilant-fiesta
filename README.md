# TIA Portal Project Release Vault

This repository contains the release archives for the TIA Portal project.

## How to Download Releases
Please navigate to the **Releases** tab in this repository to find and download the compressed `.zap18` files for specific version tags.

## Developer Setup (Git Hooks)
To automatically archive and upload release assets whenever you push a new tag, configure the pre-push hook:
1. Open a PowerShell console in the repository root and run:
   ```powershell
   powershell -ExecutionPolicy Bypass -File .\Install.ps1
   ```
2. Input your Project Server and configuration details in the GUI window.
3. Click **Install**.

This will install the archiver utility to your system and configure this repository's Git hooks.
