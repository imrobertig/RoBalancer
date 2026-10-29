# RoBalancer

**An open-source Roblox game balance toolkit.**

RoBalancer models a game's linear upgrade economy, estimates progression time, flags potential balance issues, and suggests specific tuning experiments.

## Features
- Upgrade cost and income progression model
- Estimated active earning time and per-upgrade waits
- Rule-based balance findings and tuning suggestions
- Cost multiplier comparison without overwriting current settings
- Import/export settings as JSON
- Export progression report as CSV
- Copyable recommendations report
- Responsive dark dashboard
- Runs locally in your browser; no login or external dependencies

## Run locally
Download/clone this repository and open `index.html` in a browser.

## Publish with GitHub Pages
1. Upload the project files to a GitHub repository.
2. Open **Settings → Pages**.
3. Choose **Deploy from a branch**, select `main` and `/ (root)`, then save.

## Important limitations
This version does **not** connect to Roblox or automatically inspect a live game/place file. You enter the game's numbers manually. The model currently handles one sequential upgrade path and does not simulate full rebirths, branching upgrade trees, offline earnings, multiple currencies, or real player behavior. Recommendations are starting points for experiments, not guaranteed fixes. Validate changes with playtests.

## Roadmap
- Import structured upgrade data
- Rebirth/prestige simulation
- Branching upgrade-tree support
- Multi-currency and zone unlock modeling
- Roblox Studio plugin for reading and exporting selected configuration data

## License
MIT. See `LICENSE`.
