# LUNA-Firmware

Distribution point for the LUNA OnStepNinja boards (NS-4000 / NS-5000X).
The on-board **Downloader** reads `manifest.json` from here over https to list firmware, apps, data and notices.

- `manifest.json` — the catalog the Downloader reads (do not rename or move)
- `bin/` — firmware images
- `apps/common/` — web apps that run on both NS-4000 and NS-5000X (Freeware, see LICENSE there)
- No personal data is sent; only these files are fetched.

Licenses are listed per item in `manifest.json` (NS-4000: GPL v3, source: https://github.com/OnStepNinja/OnStepNinja-NS4000; NS-5000X: PolyForm Noncommercial).

**Test distribution:** the firmware images here are for testing and are marked "test" in LUNA Base.
