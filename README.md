# jarrunner.github.io

Download files for [jr](https://github.com/jarrunner/jr), served by GitHub Pages at https://jarrunner.github.io.

- `hello/` — the end-to-end example: `hello/<version>/` holds the app's jar and its jr exes, and `hello/update.json` is the update file the exes read for `-Xjr:update-check` and `-Xjr:update`. Every exe and jar is pinned by its SHA-256, so jr refuses anything that does not match, wherever it was served from.
