# Mac125 Releases

Official macOS release artifacts and release notes for Mac125 (no source code).

## What This Repository Contains

- macOS release artifacts (`.dmg`, `.zip`)
- release notes
- checksum files
- install and support information

## Important

- This repository does not contain source code.
- Current release builds are unsigned.

## Install (macOS)

1. Download the latest `.dmg` or `.zip` from Releases.
2. If using `.dmg`, open it and drag `MacUniden125.app` to `Applications`.
3. If using `.zip`, extract then move `MacUniden125.app` to `Applications`.
4. On first launch, if macOS blocks the app:
   - right-click `MacUniden125.app` and choose `Open`
   - confirm `Open` in the security prompt

## Verify Downloads

Use `SHA256SUMS.txt` to verify artifact integrity.

Example:

```bash
shasum -a 256 MacUniden125_v0.3.4_macos.dmg
shasum -a 256 MacUniden125_v0.3.4_macos.zip
```

## Support

- Email: `gw3jvb@gmail.com`
- Discord: <https://discord.gg/89BugNgZN9>

## Support Development

- PayPal.me: <https://www.paypal.com/paypalme/JohnVincentBurns>
- Buy Me a Coffee: <https://www.buymeacoffee.com/reflectingme>
