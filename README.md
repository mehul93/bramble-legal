# Bramble public pages

Served by GitHub Pages for the Bramble iOS app.

- Support: https://mehul93.github.io/bramble-legal/support/
- Privacy policy: https://mehul93.github.io/bramble-legal/privacy/

- Feature flags: https://mehul93.github.io/bramble-legal/flags.json

The support and privacy pages are generated from the app repo (`bramble/Legal/privacy-policy.html`, `bramble/Legal/support.html`) by `scripts/publish-web-pages.sh`; edit them there.

`flags.json` is edited here directly: set a feature to `true` under `"release"` to switch it on in the App Store app, or under `"debug"` for development builds. It takes about a minute to go live.
