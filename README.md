# himanshu737936.github.io

Root site for GitHub Pages. It exists so the Chronos3D Android app can verify
itself against this origin.

- `/.well-known/assetlinks.json` — Digital Asset Links statement for the
  Chronos3D Android package (`io.github.himanshu737936.twa`). Android reads this
  file at launch; when the signing certificate matches, the app runs without a
  browser address bar.
- `index.html` — redirects visitors to the app at `/chronos3d/`.

The app itself lives in the [chronos3d](https://github.com/himanshu737936/chronos3d)
repository. If the signing key changes (new keystore, new PWABuilder package),
the fingerprint here must be updated too.
