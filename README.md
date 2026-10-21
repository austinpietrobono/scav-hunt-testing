# The Cape of No Hope

Phone games for the Halloween hunt. Each stop has its own folder, so each QR code points at one address.

| Stop | Address |
|---|---|
| Menu (for testing) | `https://<username>.github.io/<repo>/` |
| The Hurling Pump, Prince Street | `https://<username>.github.io/<repo>/pump/` |
| The Mannenberg Pipes, Bloem Street | `https://<username>.github.io/<repo>/mannenberg/` |

## Publish

1. Upload everything in this folder to the root of a GitHub repo (keep the `pump` and `mannenberg` folders).
2. Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/ (root)`.
3. Wait a minute or two for the address to go live.

## Edit

Each game has a `CONFIG` block near the top of its script with the clue and code word.
In the Mannenberg game, `needed` sets how many of the seven pipes must be heard (lower is easier).
Pressing and holding "Bloem Street" for 3 seconds opens the Mannenberg clue.
