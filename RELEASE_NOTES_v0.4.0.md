# Mac125 v0.4.0

Release date: 2026-03-06

## Highlights

- Added explicit channel clear workflow in the editor with new `Clear Selected` action.
- Added bulk clear actions in the main action panel:
  - `Clear Range`
  - `Clear Bank`
- Added confirmation and safety behavior for bulk clears:
  - clear actions update table data only (no scanner write until write actions are run)
  - partial-load handling warns when scope is not fully loaded and allows clear of loaded rows only
- Aligned blank-channel placeholder handling with write validation (`name=""`, `freq=0` clears are now valid).
- Improved transient USB error guidance (including normalized `Errno` wording and reconnect hints).
- Clarified NFM mode behavior in UI/help text.
- Updated pre-release modal to show the current app version.

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
- `Mac125_v0.4.0_macos.dmg`
- `Mac125_v0.4.0_macos.zip`
- Intel (`x86_64`):
- `Mac125_v0.4.0_macos_x86_64.dmg`
- `Mac125_v0.4.0_macos_x86_64.zip`
- `SHA256SUMS.txt`

## Support

- Discord (best support channel): <https://discord.gg/89BugNgZN9>
