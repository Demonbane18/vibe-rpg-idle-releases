# VibeRPG Idle releases

Downloads for VibeRPG Idle, a pixel-art idle RPG for the macOS menu bar. The source code is private; this repository only holds releases.

Each release has:

- The macOS app as a zip. It isn't notarized yet, so the first time you open it, right-click the app and choose Open.
- `latest.json` and a signed `.pck` update pack. The game downloads these by itself and checks the signature against the key built into the app before it installs anything.

Releases are built, signed and published by the game's CI when a version tag is pushed.
