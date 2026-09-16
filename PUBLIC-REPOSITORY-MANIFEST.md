# Public Repository Manifest

Repository role: release and documentation repository. It does not contain the proprietary Velvet Wire Studio application source.

## Explicit allowlist

- `.gitignore`
- `README.md`
- `LICENSE-NOTICE.md`
- `SECURITY.md`
- `SHA256SUMS.txt`
- `SOURCE-AVAILABILITY-NOTE.md`
- public preparation/audit documents at the repository root
- `docs\INSTALLATION.md`
- `docs\UPDATE-AND-REPAIR.md`
- `docs\UNSIGNED-BUILD.md`
- `docs\PROJECT-FORMAT.md`
- `legal\TERMS-OF-USE.md`
- `legal\THIRD-PARTY-LICENSES.md`
- `legal\THIRD-PARTY-NOTICES.md`
- `release-notes\0.1.0.md`
- `assets\screenshots\README.md`

## Excluded by design

- application source code and private Git history
- installer executables and renderer source ZIPs in normal Git history
- development candidates, unpacked applications, `app.asar`, Git bundles, and source snapshots
- private/commercial music, audio, or video
- Persona/reference screenshots and template assets
- personal projects, QA renders, preservation data, VirtualBox files, and internal legal records
- secrets, credentials, certificates, and private keys

The installer and renderer corresponding-source ZIP are planned as GitHub Release assets only.
