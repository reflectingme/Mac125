# Mac125 v0.3.5

Release date: 2026-03-01

## Highlights

- App bundle now installs as `Mac125.app` (Finder label: `Mac125`).
- Distribution artifacts are now named with the Mac125 brand:
  - `Mac125_v0.3.5_macos.dmg`
  - `Mac125_v0.3.5_macos.zip`
- Existing startup pre-release notice and update-check flow retained.
- In-app update checker continues to use the public distribution repo release feed.

## Distribution Notes

- This build is unsigned.
- If macOS blocks first launch, right-click the app and choose `Open`.
- If macOS still blocks, go to:
  - `System Settings` -> `Privacy & Security`
  - choose `Open Anyway` / `Allow Anyway` for the blocked app
- If needed, run:

```bash
xattr -dr com.apple.quarantine /Applications/Mac125.app
```

## Artifacts

- `Mac125_v0.3.5_macos.dmg`
- `Mac125_v0.3.5_macos.zip`
- `SHA256SUMS.txt`
