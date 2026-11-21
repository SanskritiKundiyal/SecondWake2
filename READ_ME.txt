SECONDWAKE — HTML / Web build

Keep index.html, index.js, index.wasm, index.pck and the audio worklet files together.

ITCH.IO:
Upload Secondwake-Web.zip without extracting it. Choose Kind of project: HTML. Enable “This file will be played in the browser.” Use a 1152x648 embed or fullscreen. This is a single-threaded export; SharedArrayBuffer support is not required.

LOCAL TEST:
Extract the folder, open a terminal in it and run:
  python -m http.server 8000
Open http://localhost:8000 in a WebGL 2-capable desktop browser.
Do not double-click index.html: it must be served over HTTP/HTTPS.
Click inside the game to enable audio and mouse capture.

Keyboard and mouse required. First load downloads roughly 90 MB of engine and game data before HTTP compression. Performance mode is the browser default. Browser progress is separate from desktop progress.

Export and resource checks passed. Interactive browser play has not been verified in the build environment because the available browser could not reach its local test server. Test the itch.io draft before publishing.

See ASSET_CREDITS.md for sourced art credits.
