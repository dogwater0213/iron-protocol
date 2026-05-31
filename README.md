# Iron Protocol

A 4-week rotating workout tracker built for your gym setup. Runs as a standalone app on your iPhone.

## Features
- 4-week exercise rotation across 5 training days (push/HIIT/legs/endurance/pull)
- Tap-to-check exercise tracking
- Weight logging per exercise with "last time" recall
- Bodyweight trend tracker with chart and goal line (210 lbs)
- Auto rest timer with audio beep
- Nutrition targets and meal framework
- Progression and scheduling guide
- Works offline after first load
- All data saves locally on your phone

## Setup (5 minutes)

### 1. Create a GitHub repo
- Go to [github.com/new](https://github.com/new)
- Name it `iron-protocol` (or whatever you want)
- Set it to **Public**
- Click **Create repository**

### 2. Upload the files
- Click **"uploading an existing file"** on the empty repo page
- Drag in all 3 files: `index.html`, `manifest.json`, `sw.js`
- Click **Commit changes**

### 3. Enable GitHub Pages
- Go to your repo → **Settings** → **Pages** (in the left sidebar)
- Under "Source", select **Deploy from a branch**
- Branch: **main**, folder: **/ (root)**
- Click **Save**
- Wait ~60 seconds, then your app will be live at:
  `https://YOUR-USERNAME.github.io/iron-protocol/`

### 4. Add to your iPhone home screen
- Open the URL above in **Safari** on your iPhone
- Tap the **Share button** (square with arrow)
- Scroll down and tap **"Add to Home Screen"**
- Name it whatever you want and tap **Add**

It'll appear as an app icon on your home screen. Opens fullscreen with no browser chrome. All your data stays on your phone in localStorage.

## Updating
If you ever want to update the workout program, just edit `index.html` in your GitHub repo and the changes go live automatically.
