# jarrunner.github.io

The home page of [jarrunner](https://github.com/jarrunner), served by GitHub Pages at https://jarrunner.github.io, and the download folder of jr's example app.

- `index.html` is the home page: one static file, no build step. `jr-icon.svg`, `jr-icon-512.png` and `favicon.ico` are jr's icon (the same as `icon/` in [jr](https://github.com/jarrunner/jr)).
- `hello/` is the end-to-end example: `hello/<version>/` holds the app's jar and its jr exes, and `hello/update.json` is the update file the exes read for `-Xjr:update-check` and `-Xjr:update`. Every exe and jar is pinned by its SHA-256, so jr refuses anything that does not match, wherever it was served from. Its URLs are read by exes already downloaded, so they never move.
