RWL Movies Web v5

Upload the CONTENTS of this folder to the root of the GitHub Pages repository RWL-Movies_Web.
The site is preconfigured for:
https://rwl-movies-gateway.rwl98.workers.dev

Public UI labels:
- Direct playback: RWL DIRECT
- Torrent/cloud resolved playback: RWL TOT
- Individual providers: Server 1, Server 2, ...

Security:
- No private API key, playback key, TMDB token, or provider secret is stored in this website.
- Private keys remain Cloudflare Worker/GitHub Secrets only.
- The public site receives short-lived signed media relay URLs from RWL Gateway.

PWA:
- manifest.webmanifest + sw.js are included.
- On iPhone, open the GitHub Pages site in Safari and use Add to Home Screen.
