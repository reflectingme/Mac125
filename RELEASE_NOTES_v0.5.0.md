# Mac125 0.5.0

Mac125 is the native Mac rewrite of the free UBC125XLT programmer. The universal Apple Silicon and Intel app targets macOS 12 or later. It remains free to use; donations are optional.

## Native display and controls

- The familiar metal/navy workspace, original LCD startup and native welcome accompany a live scanner LCD, explicit connection and clear progress/cancellation results.
- Uniden Faithful preserves the original neutral display. Mac125 Enhanced adds Amber, Green, Blue, Red and Yellow LCD palettes and restrained matching accents.
- Fixed BNK/SRC positions keep 1–9 and 0 for bank/range 10 aligned. Enhanced enabled digits are black, disabled digits subdued and the current digit inverted. Fresh partial/reception frames retain confirmed membership within bounded continuity rules.
- Hold/Resume is available in both styles. Scan/Search bank or range toggles are available only in Mac125 Enhanced. These user-hardware-confirmed controls act immediately, require acknowledgement and fresh matching status, and never retry automatically. Direction remains display-only.
- Main-workspace VOL/SQL controls read levels explicitly and verify adjustments. Priority offers Off, Do Not Disturb, Priority Scan and Priority Plus, subject to scanner acceptance and verified readback.

## Channels, writes and local tools

- Friendly CTCSS/DCS choices preserve raw values. Search, sorting, Hide Empty Channels and Locked Out Only compose with loaded bank scopes and preserve row identity and edits.
- Move / Reorder previews a channel or contiguous block within one bank, with explicit replacement/source-clear review and local Undo/Redo. Drag/drop uses the same guarded local preview. Saving a file never moves scanner memories.
- Write Selected, Write Range and Write All retain explicit target confirmation, exact-target backups, acknowledgements and per-target verified readback. Only explicit clears create deletion intent. Partial or uncertain results remain visible; there is no automatic ambiguous-write retry.
- Write Selected Memory uses the same one-memory safety workflow with a brief local LCD preview after verified success; it does not tune the scanner. Legacy Fast Mode is retired.

## Multi-bank reads

- Command-click supports non-contiguous bank selection; Shift-click selects a contiguous range from the last clicked bank.
- Read From Scanner reads only the selected banks’ 50-memory ranges, skipping the broad gaps. Read All remains the explicit 1–500 operation.
- Bank selection sends no command. It does not expand write/clear scopes. Set Range restores contiguous reading; App Help explains selection and retained partial reads.

## Custom Search and Scanner Settings

- Custom Search supports complete range reads and reviewed single-range edits to limits and Enabled, with fresh readback and confirmed cleanup. It does not start Search or change channel memories.
- Scanner Settings separates verified values from local drafts for Contrast, Backlight, Key Beep, Scan Channel Groups and supported Search delay/tone options. Unmapped Close Call and Service Search fields remain read-only.
- Settings and Priority operations temporarily use Programming Mode. EPG returns the scanner to Scan Hold; the result explains how to resume on the physical scanner. Uncertain operations preserve details and require explicit reconnect/refresh.

## Live Activity and Close Call

- One shared Live Activity Log captures only while connected and explicitly logging. Stop, closure, protected operations, disconnect or error stop capture; it never resumes automatically or recovers activity from time away from the Mac.
- Saved rows retain observations, counts, timestamps and bounded raw evidence. Fresh scanner evidence identifies Close Call where supported; not every entry is a Close Call hit, and ambiguous observations remain Mode not confirmed. No transmitter/service is inferred from frequency.
- Entries persist locally until confirmed Clear Log. CSV export is explicit. The log remembers user window placement and keeps controls visible while records scroll.
- Store Selected Live Activity reads a chosen memory fresh, previews the proposal, then uses the existing reviewed backup/write/readback workflow. Nothing is stored to the scanner automatically; the activity remains saved regardless of outcome.

## Files, Help and support

- Compatible CIN text imports offer local previews and line-level warnings; saves are atomic. Unsupported readbacks and raw fields are retained without granting write permission.
- Backup browsing/restoration imports into the local table only. Export Diagnostics produces a local ZIP with raw scanner data excluded unless explicitly requested.
- App Help now has seven clearly labelled sections in a two-row navigation control. Support includes separate bundled Release Notes, website, email, Discord and optional donation links. External destinations open only when clicked.
- The welcome explains migration, untouched exports/backups and keeping the previous app for rollback. Its device-local opt-out is unchanged.

## Known limitations / deferred items

- The direction arrow is read-only in both styles; clickable direction control is unavailable.
- Factory reset is intentionally unavailable. Weather support is not provided.
- Close Call and Service Search settings are read-only where UBC125XLT mapping is not established. Supported Search delay/tone controls do not imply support for all regional Close Call settings.
- Global Lockouts is currently being investigated for the UBC125XLT and is hoped to arrive in a future update. Its button displays local information only.
- Once per launch, after the welcome, Mac125 checks GitHub Releases and notifies only for a newer stable version. Later and exact-tag suppression are available. Download Latest opens the universal DMG or release page only when clicked. Offline/error checks stay silent. There is no automatic in-app updater: download, installation and app replacement remain manual. The Support Releases route remains available.
- Hardware confirmation of Hold/Resume and numeric bank/range keys does not establish every settings, Priority, audio or Custom Search combination. Unsupported values remain guarded; regional acceptance must not be inferred from related-model documentation.

## Installation and compatibility

Mac125 0.5.0 (1) uses manual DMG installation. The app is **ad-hoc signed and not notarised**; it has no Developer ID signature. Follow the bundled installation and quarantine-unblock guidance for a copy from a source you trust.

The universal app targets macOS 12 or later. A universal build and macOS 12 target alone do not establish runtime support on every intended Mac. Hardware behaviour for combinations not already confirmed remains subject to validation; no new hardware validation is claimed by these notes.
