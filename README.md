# Duette: Arcade content updates

Public JSON content and balance updates for the Duette: Arcade TestFlight app.

The app checks `testflight/manifest.json` over HTTPS, validates compatibility and the payload SHA-256, and applies a complete valid update on its next launch. It continues using bundled or cached content offline.

This repository contains no app source code, signing credentials, user saves, or personal information. Native code and gameplay feature changes ship through a new TestFlight build.

Publish a versioned JSON payload before updating the manifest. Keep previously published payload files available for devices already downloading an update.
