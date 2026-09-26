# Zeytun Releases

Official builds and auto-update distribution repository for **Zeytun** — a modern, high-performance desktop client for macOS.

## Downloads

Download the latest release from the [Releases](https://github.com/zeytun-labs/zeytun-release/releases) page:

- **macOS (Apple Silicon / arm64):** `zeytun_<version>_aarch64.dmg`

### Installation Note (Gatekeeper)

For ad-hoc unsigned builds on macOS, remove the quarantine attribute if prompted:

```bash
xattr -dr com.apple.quarantine /Applications/zeytun.app
```

## Update Channel

- **Desktop Bundles & Updater Artifacts:** Each release contains signed update packages (`.app.tar.gz`, `.sig`) and the update manifest (`latest.json`).
- **Core Engine:** Built on [zeytun-core](https://github.com/zeytun-labs/zeytun-core) (GPL-3.0).
