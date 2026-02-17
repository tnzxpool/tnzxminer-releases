# TNZXMiner Beta Releases

Privacy-first Monero mining client with integrated wallet and messenger.

## Downloads

| Platform | File | Size |
|----------|------|------|
| Windows 64-bit | [TNZXMiner-v16.1.0-beta-win64-setup.exe](https://github.com/tnzxpool/tnzxminer-releases/releases/download/v16.1.0-beta/TNZXMiner-v16.1.0-beta-win64-setup.exe) | ~8 MB |
| Linux DEB | Coming soon | - |
| Linux RPM | Coming soon | - |

## Important: XMRig Download

TNZXMiner does **NOT** bundle XMRig directly. On first launch:

1. The app will detect that XMRig is not installed
2. Click "Install XMRig" to automatically download from GitHub
3. The app will configure Windows Defender exclusions (admin required)
4. XMRig will be installed to `%LOCALAPPDATA%\TNZXMiner\xmrig\`

**Why?** This approach:
- Avoids licensing complications
- Reduces installer size
- Lets you use the latest XMRig version
- Avoids false-positive antivirus detections in the installer

## Quick Start

1. Download and run the installer
2. Create or import a wallet (25-word mnemonic)
3. Click "Install XMRig" when prompted
4. Click "Start Mining"

## Default Pool

The app connects to `tnzxpool.com:3333` by default.

## Features

- Monero mining (RandomX)
- Integrated wallet (create/import, 5-wallet color system)
- E2E encrypted messenger
- DNS system (.tnzx domains)
- P2P network

## Requirements

- Windows 10/11 64-bit
- 4GB RAM minimum
- CPU with AES support
- Internet connection (for XMRig download)

## Antivirus Notes

Mining software is often flagged by antivirus programs (false positive). TNZXMiner will:
1. Automatically request Windows Defender exclusions
2. Guide you to add exclusions for other antivirus software

## Beta Testing

Please report issues at: https://github.com/tnzxpool/tnzxminer-releases/issues

## Contact

- Email: tnzx@proton.me

---

*Privacy is not a feature. It's a right.*
