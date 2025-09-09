# TXT Mirror & Offline Loader (Rev 5)
This adds a TXT-only mirror of all configs for models that can't fetch JSON.

- Primary: JSON files under /cfg/ (as before)
- Fallback: TXT mirrors under /txt/ (pure text, no JSON required)

Use this loader in your chat:
Load manifest from: https://<username>.github.io/<repo>/manifest/v1.json
Use the EXECUTOR, STRICT mode, and OUTPUT CONTRACT from the manifest. Reply only "OK." on load.
If you cannot fetch files, read /LOADER.txt and the TXT mirrors under /txt/ and continue.
Begin Day 1 in [PLANNING].
