# Four Ahead
Static, private-by-design Connect 4 tutor. No accounts, API keys, dependencies or external requests. Progress is stored in the current browser's local storage; clearing site data removes it. No synchronization across devices.

## GitHub Pages
Create a repository (public if using GitHub Free), upload the contents of this folder to its root, commit to `main`. In Settings > Pages choose Deploy from a branch, main, / (root), Save. Open the published URL shown by GitHub. On iPad open in Safari, Share > Add to Home Screen (enable Open as Web App if shown). Open online once to cache files for offline use. Service worker updates automatically; restart the app after deploying updates. No Mac or Xcode required.

## Coaching
My coach selects generated legal scenarios; Academy selects a skill; Play a game uses a computer opponent; Mistake replay revisits saved positions. Compare moves labels only completed exact searches or tactical proofs as proven. Other moves carry a heuristic estimate, not a mathematical result. Search has a short time budget; early positions may remain unresolved. Threat height introduces support and parity awareness, not a full parity curriculum. Learning signals are tentative, and spacing uses completed attempts rather than calendar time.

## Local use
Open index.html with a local HTTP server (e.g. `python3 -m http.server 8000` then localhost:8000). The separate single-file edition works without a server, but has no offline-install service worker.

## Pilot testing (2.1)
Open Parent / testing tools and enable pilot logging. Export the JSON log after sessions and share it manually for analysis. Logs are local, capped at 6000 events, and can be deleted independently of learning progress. No network analytics.
