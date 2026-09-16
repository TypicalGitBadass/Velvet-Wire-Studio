# Installation

## Requirements

- Platform: Windows x64
- Account: not required
- Internet for ordinary use: not required
- Node.js: not required
- System FFmpeg: not required
- Precise minimum Windows version: supported/tested platform information requires owner confirmation

## Install Velvet Wire Studio 0.1.0

1. Download `Velvet-Wire-Studio-Setup-0.1.0.exe` from the official GitHub Release.
2. Optionally verify the installer:

   ```powershell
   Get-FileHash -Algorithm SHA256 -LiteralPath '.\Velvet-Wire-Studio-Setup-0.1.0.exe'
   ```

   Expected SHA-256:

   `12C7823E6BDD92B44E813D0F03DD3CE122CD82C280DC8E8F75B6D98DE21E445C`

3. Run the installer and follow the ordinary Windows prompts.
4. Launch Velvet Wire Studio from the Start menu or installed shortcut.

## Unsigned-build notice

Version 0.1.0 is currently unsigned. Windows may display Unknown Publisher, Microsoft Defender SmartScreen, or an additional confirmation prompt. Proceed only if you obtained the installer from the official release location, trust that source, and the SHA-256 matches.

Do not disable SmartScreen, Microsoft Defender, antivirus software, or other Windows security protections.
