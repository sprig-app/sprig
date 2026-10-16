# Sprig

Sprig is a small self-hosted companion for playback sources and subtitles. You run it yourself — on a Mac, a Windows PC, a Linux server, or a free host such as alwaysdata — and connect it to the Vesper app like a media server. There is no hosted Sprig service, account, or analytics.

This repository only publishes ready-to-run builds. Download the file for your system from the [latest release](https://github.com/sprig-app/sprig/releases/latest):

| System | File |
| --- | --- |
| Mac with Apple silicon | `Sprig-<version>-macos-arm64.dmg` |
| Mac with Intel | `Sprig-<version>-macos-x64.dmg` |
| Windows | `Sprig-<version>-windows-x64.zip` |
| Linux server or free host (most) | `Sprig-<version>-linux-x64.tar.gz` |
| Linux on ARM (e.g. Ampere, Raspberry Pi 64-bit) | `Sprig-<version>-linux-arm64.tar.gz` |

Each release lists SHA-256 checksums in `SHA256SUMS`.

After Sprig starts, open it in a browser. Its built-in **Hosting guide** walks through setup, sharing outside your home, backups, and an AI-assistant setup brief you can paste into Claude, ChatGPT, Gemini, or another assistant.

The Mac builds are not notarized; macOS may ask you to approve Sprig in **System Settings → Privacy & Security** the first time. The Windows build has not yet been tested on Windows.

Sprig does not provide or host any media. It only returns playback links and subtitles from sources you configure yourself.

Licensed under the MIT License. See `LICENSE` and `THIRD_PARTY_NOTICES.md`.
