# Vimeo Embed Builder

Minimal tool to customize Vimeo embed appearance and copy the iframe code. All changes update the preview and code live.

## Use

1. Open `index.html` in a browser (or run a local server).
2. Paste a Vimeo **video ID** or **URL** (e.g. `1051366301` or `https://vimeo.com/1051366301`).
3. Toggle options (badge, autoplay, loop, muted, controls, fullscreen, byline, portrait, title, pip).
4. Copy the generated embed code from the section below the player.

## Options

| Option | Description |
|--------|-------------|
| Badge | Show/hide Vimeo badge |
| Autopause | Pause when another Vimeo video plays on the page |
| Autoplay | Start playback automatically |
| Loop | Restart video when it ends |
| Muted | Start muted (needed for autoplay in many browsers) |
| Controls | Show play bar and controls |
| Fullscreen | Show fullscreen button |
| Byline | Show creator name |
| Portrait | Show creator portrait |
| Title | Show video title |
| Picture-in-picture | Enable PiP button |

## Unlisted videos

Use the full Vimeo URL including the `h` parameter (e.g. `https://vimeo.com/123456?h=abc123`). The tool keeps the hash and adds it to the embed URL.

## Tech

Single HTML file, no build step. Works offline after first load.
