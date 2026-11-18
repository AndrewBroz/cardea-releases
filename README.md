# Cardea releases

Signed release files for the Cardea browser extension, served by GitHub Pages.

- `firefox/update.json`: the update manifest Firefox polls (the extension's `update_url`).
- `firefox/cardea-<version>.xpi`: Mozilla-signed, unlisted builds.

Files here are written by `npm run firefox:publish` in the main Cardea repo.
Don't edit `update.json` by hand.
