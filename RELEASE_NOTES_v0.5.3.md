# Mac125 0.5.3

## CTCSS and DCS selection fix

- Fixed disappearing CTCSS tone and DCS code submenus in the local channel editor, both while disconnected and while connected with live scanner status updates.
- Tone selection continues to edit the local draft only. Applying local edits and writing changes to the scanner remain separate, explicit steps.

## Thanks

Thank you to Andrew Pennock for reporting the CTCSS dropdown issue and providing the details that helped us reproduce it and correct the CTCSS and DCS menus.

## Save File feedback

- Save File is now disabled while any local channel draft remains unapplied, including drafts hidden by the current bank or table filters.
- The Channel Workspace explains the restriction in amber directly below Load File / Save File. Saving becomes available again only after every draft is applied or discarded.
- An active in-table edit is reflected immediately. Returning the field to its original value does not create a false unfinished edit.

## Live Activity Log improvements

- Captured channel names, memory numbers and Scan-bank numbers now have dedicated columns and are included in filtering and CSV export. They come from recorded scanner evidence, not the editable Channels table. Unavailable or conflicting details stay unconfirmed; Search ranges and Close Call are not presented as channel banks.
- Corrected recognition of the scanner's rotating SCAN text during activity capture, using the complete matching status layout. Raw scanner evidence remains available for inspection.
- Compact, wrapped headings make the activity table easier to read. Column widths are remembered, and restored window placement chooses the display with the greatest overlap when using multiple monitors.

These changes preserve explicit connection, local editing, reviewed scanner writes, backups and verified readback. Downloads and installation remain manual.
