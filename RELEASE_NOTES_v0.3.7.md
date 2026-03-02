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
