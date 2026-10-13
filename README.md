# Ruckus Launcher catalog

The signed list of mods that [Ruckus Launcher](https://github.com/ExportServers) shows, plus
the mod downloads (attached to GitHub Releases).

- `catalog.json` - games, mods, versions, SHA-256 hashes, news
- `catalog.json.sig` - Ed25519 signature of `catalog.json`; the launcher rejects anything
  that doesn't verify against its built-in public key

Edits here have no effect unless they are re-signed with the private key.
