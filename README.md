# SeuPut Studio Releases

This public repository contains signed desktop installers and update metadata for **SeuPut Studio**.
Source code remains in the private `SeuPut0705/seuput-website` repository.

## Downloads

Use the latest GitHub Release for the supported platforms:

- macOS Apple Silicon (`arm64`): DMG
- macOS Intel (`x64`): DMG
- Windows 64-bit (`x64`): NSIS installer

Every release includes SHA-256 checksums. Stable and beta releases are built by GitHub Actions,
code-signed, and on macOS notarized by Apple before publication.

## Automatic updates

Installed Studio apps read the release metadata in this repository through `electron-updater`.
Do not manually modify `latest.yml`, `latest-mac.yml`, beta metadata, or blockmap files.
