# ebartosh.github.io

Public project homepage for [ebartosh](https://github.com/ebartosh), hosted with GitHub Pages at https://ebartosh.github.io/.

The Lifeboat project page is https://ebartosh.github.io/lifeboat/ and its source repository is https://github.com/ebartosh/lifeboat.

Lifeboat is an emergency Android client for Solana positions. It reads state directly from the chain and builds supported withdrawal, repayment and claim transactions using an RPC endpoint and an external wallet when protocol websites or backends are unavailable.

## Android app association

`.well-known/assetlinks.json` associates this host with the Android package `app.lifeboat.mobile` and the signing certificate of the current Lifeboat prototype. It must be served at https://ebartosh.github.io/.well-known/assetlinks.json. `.nojekyll` preserves the dot-prefixed directory during publication.

The fingerprint was verified against the installed prototype APK on October 8, 2026. It is a test signing certificate. Update the association when the application signing certificate changes; use the app signing certificate for builds distributed through Google Play App Signing.

Domain association does not establish a security audit or guarantee wallet approval.

## Publication

GitHub Pages publishes the default branch from `/` with HTTPS. The site contains static HTML and public certificate metadata.
