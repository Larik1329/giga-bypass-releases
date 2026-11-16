# Giga Bypass downloads

Public binary distribution only. Client application source, server settings and credentials are not stored in this repository.

Only reviewed releases listed below have been published; downloads were fetched anonymously and hash-verified. Android 1.1.0 is a public TEST release: per-user VPN activation is pending the dedicated server provider configuration. Do not obtain or redistribute earlier private test APKs: they are not public distributions.

## Access
The public Android client uses an administrator-issued, expiring invitation and its own per-device session. Installing a binary does not grant service access. New users have no access until the administrator explicitly grants it. No shared service token, private VPN profile, room link or provider credential is embedded in public builds.

## Capabilities
Android and Windows releases describe their exact tested capabilities separately. The experimental legacy Windows manual-room joiner is not a full Android/Remnawave-parity client. A successful package build is not Windows-driver or physical Android VPN acceptance. Telemost has finite one-joiner room capacity; unsupported enforcement is never labelled enforced.

Use only authorised accounts/rooms. Never post access invitations, profiles, private room links, tokens or logs containing them in public issues.

See THIRD-PARTY-NOTICES.txt and the notices/licenses shipped with each asset. Published releases include checksums and the applicable upstream corresponding native-source archive.

## Verified downloads
- [Windows 1.0.1 — EXPERIMENTAL manual-room joiner](https://github.com/Larik1329/giga-bypass-releases/releases/tag/windows-v1.0.1-experimental). Not a full Remnawave client; real Windows VPN/driver/DPAPI acceptance remains unverified.
- [Public upstream native sources and licenses](https://github.com/Larik1329/giga-bypass-releases/releases/tag/native-sources-v1.0.1). Not private application source or an installer.

- [Android 1.1.0 TEST — activation pending](https://github.com/Larik1329/giga-bypass-releases/releases/tag/android-v1.1.0-test). Requires a fresh administrator invitation and explicit grant. Not a drop-in working upgrade for private1.0.0; read TEST-LIMITATIONS before installation.
