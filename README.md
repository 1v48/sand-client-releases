# Sand Client releases

Public distribution repository for the standalone Windows Sand Client launcher. This repository contains public release information and banner content only. Launcher source, account credentials, private signing keys and local configuration backups do not belong here.

## Current status

- Local Windows installers exist and are being tested.
- No downloadable release has been published here yet.
- Automatic application updates are not enabled yet. They require signed Tauri update artifacts and an end-to-end upgrade test.
- `content/banners.json` is intentionally empty. The launcher still uses bundled banner previews; remote banner delivery is not enabled yet.
- Minecraft Services login has returned HTTP 403 during owner testing. Full authentication, ownership verification and authenticated gameplay are not claimed working.

## Planned updates

Application releases will use versioned GitHub Releases with signed update metadata. Banner copy and approved artwork will use the separate public content feed, allowing content changes without a new installer once the client integration is enabled.
