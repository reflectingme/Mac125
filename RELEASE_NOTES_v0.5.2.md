# Mac125 0.5.2

Mac125 0.5.2 is a free update for the native macOS companion app for the Uniden UBC125XLT. It is a universal Apple Silicon and Intel build for macOS 12 or later.

## Workspace and editing improvements

- This release fixes local editing after bank/filter changes: an ordinary row click selects that row alone, including clearing hidden selections. Command/Shift multi-selection and filter-only selection retention remain available. No scanner command or write safeguard changes.

- Secondary workspace controls have their own matching two-column panel: Custom Search and Live Activity Log; Global Lockouts and Priority; Scanner Settings. Existing action availability and scanner safeguards are unchanged.

- Choose Standard or Wide workspace layouts from the display selectors. Mac125 remembers the selected layout, separate Standard/Wide window frames, and the Wide Audio-panel state.
- Wide layout gives the channel table substantially more usable vertical space on lower-height displays, while retaining the scanner display and Channel Workspace on the left.
- The Audio panel can be collapsed in Wide layout whenever more vertical room is needed. This is a local display preference and does not alter scanner audio levels.
- The disconnected display now gives clear guidance to press Connect in the header. Connection remains explicit.
- The channel toolbar has a stable three-row arrangement for bank/range controls, search and sorting, then filters and table actions.
- Edit a channel directly in the table with double-click or F2, or open the compact Edit Details sheet. Tab and Shift+Tab move through editable fields and rows; Return and Shift+Return move vertically; Escape cancels the active cell edit.
- Empty or unloaded positions can now be used to create local channel drafts. Mandatory channel information is validated before apply, file save, backup/export, or scanner-write preparation.
- Optional Local Notes appear in a narrow table column and the Edit Details sheet. Notes are retained with local recovery, compatible files and backups, but are never written to the scanner.
- Local channels and incomplete drafts recover after relaunch. Restored drafts remain unapplied, and recovery never authorises a scanner write.

## Companion Sharing

- Free, explicit local-network sharing with paired iPhone/iPad companions: live LCD, loaded-channel browsing, guarded scanner controls and selected-bank/all reads. Sharing starts off each launch.
- Shared activity logging, host-owned sleep timer, local notes/review flags and channel favourites; friendly paired-device names, connected indicator and deliberate revocation.
- Public Mac125 uses its own pairing trust. Private-host pairings and data are not migrated automatically. Existing public data locations remain unchanged.
- The Mac remains the sole USB owner. No remote memory writes, automatic command retries or internet relay; Close Call remains read-only on companions and Tune & Hold remains unavailable.

## Safeguards and existing features

- Explicit connection, review, confirmation, exact-target backup, acknowledgement, readback verification and EPG cleanup remain required for scanner writes. There is no automatic ambiguous-write retry.
- Live LCD styles and palettes, Hold/Resume, Enhanced numeric controls, activity logging, Custom Search, Scanner Settings, Audio and Priority retain their existing behaviour.
- The direction arrow remains read-only. Global Lockouts, factory reset and unverified settings remain unavailable. The Premium Virtual Channel Manager is not part of this free release.
- Mac125 checks GitHub Releases once at launch after the welcome. Downloads and installation remain manual; nothing is downloaded, installed or replaced automatically.

## Thanks

Special thanks to David (Astra) for his patience and perseverance in reporting the channel-selection issue and working with John over several days to help track it down and resolve it.

## Installation and compatibility

Mac125 0.5.2 targets macOS 12 or later. The app is ad-hoc signed and not notarised; follow the bundled installation and quarantine-unblock guidance when installing a copy from a source you trust.
