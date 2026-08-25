# Trading Mastery — Website Version

This is the simple version: one free account (GitHub), no coding tools, no functions,
no API keys. You edit everything with Claude, then upload the changed files here.

## What's in this folder

```
index.html            <- the whole site (all chapters + Morning Minutes)
manifest.json          <- lets your phone "Add to Home Screen" like a real app
icons/                  <- the app icon
data/market-data.json  <- the data Morning Minutes shows (you update this with Claude's help)
```

## One-time setup (about 10 minutes)

1. Go to **github.com** and sign up (free, no card).
2. Click **New repository**. Name it anything (e.g. `trading-mastery`). Leave everything
   else default. Click **Create repository**.
3. On the new repo's page, click **uploading an existing file**.
4. Drag in every file and folder from this project (`index.html`, `manifest.json`,
   `icons/`, `data/`) — all at once. Click **Commit changes**.
5. Go to the repo's **Settings** tab → **Pages** (left sidebar).
6. Under "Build and deployment", set **Source** to **Deploy from a branch**, **Branch**
   to **main**, folder to **/ (root)**. Click **Save**.
7. Wait about a minute, then refresh that Pages settings page — it'll show your live
   URL, something like `https://yourusername.github.io/trading-mastery/`.
8. Open that URL on your phone (Safari or Chrome), then use **Add to Home Screen** —
   it'll open full-screen like a real app from then on.

That's it. No Vercel, no Finnhub, no environment variables, no functions.

## How updates work from here on

Nothing changes about how we work together. You keep coming back to this chat to build,
edit, and ask for changes, exactly like now. When something's ready:

1. Claude gives you the updated file(s) — usually just `index.html` or
   `data/market-data.json`, whichever changed.
2. Go to your GitHub repo, open that file, click the pencil (edit) icon, replace the
   content, and click **Commit changes**. (Or drag a replacement file in via **Add file
   → Upload files** if it's easier — GitHub will ask if you want to overwrite the
   existing one.)
3. The live site updates automatically within about a minute. No redeploy step, nothing
   else to touch.

For small data tweaks (a new Price Watch level, an updated Morning Read entry, this
week's outlook), Claude can just tell you exactly what to paste into
`data/market-data.json` — you won't need the whole file re-sent every time.

## Coming back to full automation later

The pieces for automatic daily price/earnings updates (Vercel + Finnhub + a scheduled
refresh) aren't in this folder, but nothing here needs to be rebuilt to add them later —
it's purely additive. When you're ready, just say so and we'll pick that up as its own
session.
