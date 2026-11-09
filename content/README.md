# Banner content

Edit banners.json on main to change launcher banners without rebuilding version 0.3.6 or later. The app refreshes on startup, every five minutes while visible, or from Settings > Launcher > Refresh banners. Empty content uses the bundled previews. Offline or invalid content uses the last valid cache.

Each item supports id, title (80 characters), description (180 characters), preview (defaults to true), optional imageUrl and optional HTTPS href. Maximum four banners. Artwork must be PNG/JPEG/WebP, at most 1MB per file, under this repository's content/assets directory. Use raw.githubusercontent.com/1v48/sand-client-releases/main/content/assets/ URLs. Keep essential copy in JSON so it stays sharp.

Example (not a paid placement):

```json
{"schemaVersion":1,"banners":[{"id":"sand-preview","title":"Sand Client","description":"Example preview — replace with approved content.","imageUrl":null,"href":"https://github.com/1v48/sand-client-releases","preview":true}]}
```

No HTML, scripts, executable commands, account data, private keys or personal files belong in the feed. Only publish approved content and artwork you have permission to distribute.
