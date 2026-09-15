# owen282000.github.io

The domain root for `owen282000.github.io`. It exists so that
`/.well-known/assetlinks.json` can be served from the root, which is where Android
looks for it when it verifies App Links for
[Life Dashboard Companion](https://github.com/owen282000/life-dashboard-companion-app).

The file must stay at that path, be served as `application/json`, and never
redirect. The fingerprint in it is the app's release signing certificate, published
in the app's `SECURITY.md`.
