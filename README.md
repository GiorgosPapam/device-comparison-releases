# Device Comparison — releases

Finished versions of the Device Comparison app, published here so installed copies can find updates.

- Each release has two files: `DeviceComparison.exe` and `update.json`.
- `update.json` describes the program (version, size and SHA-256 fingerprint) and is signed with the app's own update key.
  The app installs a version only if that signature is valid and the downloaded program matches it exactly.
- Installing an update is always the user's choice, from inside the app.

This repository holds no source code and no data.
