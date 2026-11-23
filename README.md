# Best Discord — downloads

This repository contains the signed catalogue and verified downloads. The development repository remains private.

## Windows

Download [Best Discord 1.0.3](https://github.com/Pada-js/best-discord-distribution/releases/download/v1.0.3/best-discord-1.0.3-windows-x64.zip), extract the whole archive, close Discord, then run `installer/Setup.exe`. Normal Discord startup is preserved.

Installer ZIP SHA256: `b2effde0b5673ff475b673f3dde4dd56086b107a4b7532218789a990a832e08f`.

The installer bundles zero mods and zero account sessions. Installed mods and their private data are kept separate from engine releases. The initial approved catalogue is empty.

## Developers

[Download the SDK and examples](https://github.com/Pada-js/best-discord-distribution/releases/download/v1.0.3/best-discord-sdk-dev2.zip). Examples are not installed automatically. Third-party mods require review before addition to the approved catalogue.

## Update trust

Catalogue, index, engine and compatibility-profile signatures use separate pinned Ed25519 authorities. Packages do not grant permissions or activate mods. Metadata expires and must be renewed by the operator. Unknown Discord layouts or binaries are refused until validation. Future Discord compatibility is not guaranteed.

The installer does not have a Windows Authenticode certificate. Ed25519 update verification is separate from Windows publisher certification.
