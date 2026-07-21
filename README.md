# Turmaline Releases

Distribution repo for [Turmaline](https://github.com/daniloneto/turmaline) — this repo only holds packaged installers, never source code.

## Download

Grab the latest installer from the [latest release](https://github.com/daniloneto/turmaline-releases/releases/latest):

- Windows: `.msi` / `.exe`
- macOS: `.dmg`
- Linux: `.AppImage` / `.deb`

## How releases get here

Pushing a tag (`vX.Y.Z`) on the [turmaline](https://github.com/daniloneto/turmaline) repo triggers `.github/workflows/release.yml`, which builds the installers for Windows, macOS and Linux and publishes them as a draft release here. Review the draft and publish it manually.
