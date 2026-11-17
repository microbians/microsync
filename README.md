# microSync

A Mac menu bar app that keeps pairs of folders in sync — mirror, update or two-way — without ever deleting a file:
anything replaced or removed is kept in an archive inside the synced folder.

This repository only holds what the app reads to offer updates:

- `release.json` — the latest version: `{"version", "url", "sha256"}`.
- the update file named in `url` (sealed; the app checks its checksum and signature before installing it).

microSync is available on Gumroad.
