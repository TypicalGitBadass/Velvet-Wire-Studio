# Velvet Wire Studio
<img width="1916" height="1077" alt="7bad23c1-5ced-4079-b089-28ef7de0613c" src="https://github.com/user-attachments/assets/efd16f0d-caad-4d42-a269-ec260f154f48" />
Velvet Wire Studio is an offline-first Windows desktop application for creating, previewing, saving, and exporting cinematic conversation scenes.

Created by **TypicalNoctis**.

## Features
<img width="1524" height="854" alt="Yellow" src="https://github.com/user-attachments/assets/a8e95eae-a6bb-4817-ae55-f207b851dd4f" />
<img width="1526" height="856" alt="Green" src="https://github.com/user-attachments/assets/4a06c8c2-74f2-4623-9941-c2a24ed4b79a" />
<img width="1527" height="859" alt="Blue" src="https://github.com/user-attachments/assets/fb68a498-9c51-4aac-a4d0-df6e6a4b12b4" />
<img width="1529" height="859" alt="Red" src="https://github.com/user-attachments/assets/4a81f852-2d33-43aa-a01a-b9e8b490dc40" />

- Create characters and author multi-character conversations.
- Compose cinematic In-Game IM presentations with controlled message rhythm.
- Add integrated Player Replies.
- Add Project Music that persists with the project.
- Import custom incoming-message and reply sound effects.
- Export still images as PNG.
- Export conversations as MP4 at supported 30 FPS and 60 FPS settings.
- Save portable `.velvetwire` projects using Project Format v2.
- Upgrade through future installers without normally uninstalling first.
- Use same-version Repair/Reinstall to restore application-owned files.
- Work without an account or internet connection during ordinary use.

## Download and install

Download `Velvet-Wire-Studio-Setup-0.1.1.exe` from the official GitHub Release. Verify it against [`SHA256SUMS.txt`](SHA256SUMS.txt), then follow the [installation guide](docs/INSTALLATION.md).

Velvet Wire Studio 0.1.1 is currently unsigned. Windows may display Unknown Publisher or Microsoft Defender SmartScreen. Continue only when the file came from the official release and its checksum matches. Do not disable Windows security features.

### Windows process behavior

Velvet Wire Studio uses Electron and Chromium-based rendering for MP4 export. Windows may temporarily show several application and rendering processes while an export is active. Render-specific processes close after rendering, cancellation, or application shutdown.

## Projects

Velvet Wire uses portable `.velvetwire` Project Format v2 files. See [Project Format](docs/PROJECT-FORMAT.md).

## Updates and repair

See [Update and Repair](docs/UPDATE-AND-REPAIR.md) for supported upgrade, same-version Repair/Reinstall, and uninstall behavior.

## Screenshots

No public screenshots are included yet. **OWNER SCREENSHOT SELECTION REQUIRED.** Only first-party, redistribution-cleared product screenshots may be added.

## Source availability

The Velvet Wire Studio application source is not currently published as open-source software. The renderer corresponding-source archive supplied with releases covers applicable bundled renderer components; it is not the complete Velvet Wire application source. See [Source Availability](SOURCE-AVAILABILITY-NOTE.md) and [License Notice](LICENSE-NOTICE.md).

## Legal

- [Terms of Use](legal/TERMS-OF-USE.md)
- [Third-Party Licenses](legal/THIRD-PARTY-LICENSES.md)
- [Third-Party Notices](legal/THIRD-PARTY-NOTICES.md)

Velvet Wire Studio is an independent product. It is not affiliated with, endorsed by, or an official product of Atlus, Sega, Persona, or any other third party.
