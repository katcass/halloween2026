# Ghostface Calling

A phone page for a Scream costume. Tap **Ring** and the phone rings like an old landline. Press **Answer** and Ghostface asks, "What's your favorite scary movie?"

- `index.html` is the whole page.
- `audio/ghostface-line.mp3` is the recorded line.

## Remote buttons

Tap "arm the remote" once after opening the page. Then:

| Button | Does |
| --- | --- |
| Right / Down arrow, Page Down, Enter, Space | Answer |
| Left / Up arrow, Page Up | Ring (press again to stop) |
| Game controller A, or D-pad right/down | Answer |
| Game controller B, or D-pad left/up | Ring |
| Any other key, or headphone play/pause | Next step: ring, answer, hang up |

## Hosting

Cloudflare Pages, connected to this repo. No build command; the output directory is the repo root. Every push to `main` redeploys.
