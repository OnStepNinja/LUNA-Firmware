# LUNA-Firmware

Distribution point for the LUNA OnStepNinja boards (NS-4000 / NS-5000X).
The on-board **Downloader** reads `manifest.json` from here over https to list firmware, apps, data and notices.

- `manifest.json` — the catalog the Downloader reads (do not rename or move)
- `bin/` — firmware images
- No personal data is sent; only these files are fetched.

Licenses differ per product and are listed in `manifest.json` (NS-4000: GPL v3, NS-5000X: PolyForm Noncommercial).
