# app-updates

Update feeds for All Good Folks apps. Each app polls its JSON file and shows an
in-app "update available" banner when the version here is newer than installed.

- `trigger.json` — Trigger (Ableton key/MIDI remapper)

Schema (all fields required except notes/minimumSystemVersion):
```json
{ "version": "1.4", "notes": "• ...", "downloadURL": "https://...", "minimumSystemVersion": "13.0" }
```
Published by `release.sh` (or Gemme's Dev → Releases panel). Public on purpose:
the raw URL must be readable without auth.
