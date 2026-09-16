# Unsigned Windows Build

Velvet Wire Studio 0.1.0 is currently distributed without an Authenticode signature. Signing was intentionally deferred by the owner for the initial release and is not a functional defect.

Windows may display Unknown Publisher, Microsoft Defender SmartScreen, or an additional confirmation prompt when the installer is opened.

Download the installer only from the official GitHub Release, verify its SHA-256 against [`SHA256SUMS.txt`](../SHA256SUMS.txt), and continue only if you trust the source. Do not disable antivirus, Microsoft Defender, SmartScreen, or other Windows security protections.

The `TypicalNoctis` publisher text shown in application metadata or Windows Installed Apps is separate from Authenticode verification. Version 0.1.0 must not be described as digitally signed.
