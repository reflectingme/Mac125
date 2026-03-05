# Mac125 v0.3.8

Release date: 2026-03-05

## Highlights

- Added live table search/filter in the main UI (name, frequency, or channel number).
- Added search controls in the action panel area with count display and clear action.
- Table sorting and search now work together for easier channel management.
- Added Intel (`x86_64`) release artifacts alongside Apple Silicon builds.

## Distribution Notes

- This build is unsigned.
- If macOS shows a warning that the app is "damaged" or not supported, this is a Gatekeeper trust prompt for unsigned apps and does not mean the app is dead.
- If the warning dialog is shown, select `Cancel` and do one of the following:

![Example macOS first-launch warning](https://raw.githubusercontent.com/reflectingme/Mac125/main/macOS_warning.png)

- If macOS blocks first launch, right-click the app and choose `Open`.
- If macOS still blocks, go to:
  - `System Settings` -> `Privacy & Security`
  - choose `Open Anyway` / `Allow Anyway` for the blocked app
- If needed, run:

```bash
xattr -dr com.apple.quarantine /Applications/Mac125.app
```

## Artifacts

- Apple Silicon:
- `Mac125_v0.3.8_macos.dmg`
- `Mac125_v0.3.8_macos.zip`
- Intel (`x86_64`):
- `Mac125_v0.3.8_macos_x86_64.dmg`
- `Mac125_v0.3.8_macos_x86_64.zip`
- `SHA256SUMS.txt`

## Support

- Discord (best support channel): <https://discord.gg/89BugNgZN9>
