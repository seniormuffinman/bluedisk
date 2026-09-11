# Blue Zone Parking

Minimal parking-disc helper for Blue Zone / "Parking with parking disc" areas.

Shows whether you can park right now, what time to set on the disc, and when you must leave. Uses device time + optional public-holiday data by Swiss canton.

## Live demo (after you enable Pages)

`https://YOUR_USERNAME.github.io/blue-zone-parking/`

## Deploy to GitHub Pages

### 1. Create the repo
1. Go to [github.com/new](https://github.com/new)
2. Repository name: `blue-zone-parking` (or any name)
3. Public → Create repository

### 2. Push this folder

```bash
cd blue-zone-parking
git init
git add .
git commit -m "Blue Zone parking disc helper"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/blue-zone-parking.git
git push -u origin main
```

### 3. Enable GitHub Pages
1. Repo → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / folder `/ (root)` → Save
4. Wait ~30–60 seconds, then open the URL shown

### 4. Install on phone
- Android Chrome: open the site → menu → **Install app** / **Add to Home screen**
- iOS Safari: Share → **Add to Home Screen**

## Features
- Live device clock
- Max stay + exact disc setting time
- Canton selector + public holidays via OpenHolidays API
- Manual public-holiday toggle
- Optional location → nearest canton
- Works offline after first load (PWA)

## Legal note
Rules based on typical Swiss Blue Zone / parking-disc signage (Signaling Ordinance). Always follow local signs.
