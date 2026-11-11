# Cadre Wallet config

Static host for the signed Cadre Wallet settings file, served at
`https://config.cadre.ag/wallet/v1.json`.

The wallet only accepts this file when its signature verifies against a key built into the
wallet, so changing the file here without that key has no effect. The same file is also served
by the Cadre API as a fallback.
