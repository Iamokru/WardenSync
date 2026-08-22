# D&D Manager Sync Data

This folder is synchronized by the Warden app (https://github.com — local-first D&D creature & combat manager).

- `manifest.json` — index of every synced object with version metadata.
- `templates/` — one JSON file per creature template.
- `campaigns/` — one JSON file per campaign (encounters are nested inside).

Do not edit these files by hand while sync is active — your local app is always the primary copy; this repo is a sync target, not the source of truth.
