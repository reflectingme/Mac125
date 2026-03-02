# Mac125 v0.3.6

Release date: 2026-03-02

## Highlights

- Improved popup/modal readability in Light Mode.
- Applied consistent contrast-safe styling to app dialogs and message popups.
- Pre-release and update dialogs now render on the same styled panel surface as the main UI.

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

- `Mac125_v0.3.6_macos.dmg`
- `Mac125_v0.3.6_macos.zip`
- `SHA256SUMS.txt`
