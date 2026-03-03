# Mac125 v0.3.7

Release date: 2026-03-02

## Highlights

- Added sortable channel table columns in the main grid.
  - Click column headers to sort ascending/descending (Frequency, Name, Delay, Priority, etc.).
- Improved write-action clarity when scanner resumes to CH1/hold after write.
  - Added explicit guidance in tooltips and status text to press `Scan` on the radio to resume.
- Included previously pending text correction in the pre-release notice:
  - "Many thankd" -> "Many thanks".

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

- `Mac125_v0.3.7_macos.dmg`
- `Mac125_v0.3.7_macos.zip`
- `SHA256SUMS.txt`

## Support

- Discord (best support channel): <https://discord.gg/89BugNgZN9>
