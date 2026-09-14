RWL Movies Web v2

1) Upload index.html, style.css, app.js and the assets folder to the root of your RWL-Movies-Web GitHub repository.
2) GitHub Pages remains: main / (root).
3) Open the site, press the gear icon, and paste the PUBLIC RWL Gateway URL only.
4) Do NOT paste RWL_PLAYBACK_KEY, TMDB token, Cloudflare token, or any secret into GitHub Pages.

This version loads real TMDB catalog/details/search through the RWL Gateway endpoints:
/v1/tmdb/home
/v1/tmdb/search
/v1/tmdb/details

The playback/source section is intentionally left for the next stage.
