# PacketSUMP Releases

This repo exists for one reason: `latest.json` here needs to be reachable over plain
HTTPS without an auth token, so the app's auto-updater can check it. The actual
source code lives in a private repo and stays there.

- `latest.json` — the update manifest the app polls on startup.
- Each GitHub Release here has the installer `.exe` attached as a release asset.

No source code, no issues, no PRs expected here — it's a distribution channel, not a
project.
