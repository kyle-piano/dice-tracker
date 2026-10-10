# Settlers' Dice Ledger

A single-page tool for tallying Catan dice rolls as you play, and comparing them live against the true 2d6 probability curve.

## What it does

- 11 tap buttons (2–12) styled after the real Catan number tokens, pips included.
- A live bar chart of your actual roll distribution vs. the theoretical 2d6 odds.
- Stats strip (total rolls, most/least rolled), undo last roll, and reset.
- Saves to the browser's local storage, so a refresh mid-game doesn't lose your tally.

No dependencies, no build step — just one HTML file (Google Fonts are loaded from a CDN link).

## Run locally

Open `index.html` directly in a browser. That's it.

## Deploy (GitHub Pages)

1. Push this repo to GitHub, if you haven't already:
   ```
   git remote add origin <your-repo-url>
   git push -u origin master
   ```
2. On GitHub: **Settings → Pages → Source** → "Deploy from a branch" → pick the `master` branch and `/ (root)` folder → **Save**.
3. GitHub publishes it at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

Any future `git push` to that branch updates the live site automatically.
