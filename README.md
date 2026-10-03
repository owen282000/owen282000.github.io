# owen282000.github.io

The domain root for `owen282000.github.io`. It exists so that
`/.well-known/assetlinks.json` can be served from the root, which is where Android
looks for it when it verifies App Links for
[Life Dashboard Companion](https://github.com/owen282000/life-dashboard-companion-app).

The file must stay at that path, be served as `application/json`, and never
redirect. The fingerprint in it is the app's release signing certificate, published
in the app's `SECURITY.md`.

`/life-dashboard-companion/ios/privacy/` is the privacy policy of the iOS app, the address
App Store Connect and the app's About screen link to. Keep it in step with the policy screen
in the app and the Privacy section of the iOS repository's README. It is not under
`/life-dashboard/`, because a project site of the `life-dashboard` repository would take over
that path.
