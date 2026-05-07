# Pokémon Center Monitor — iPhone PWA

## How to host it (free, 5 minutes)

### Option A — Netlify Drop (EASIEST, no account needed)
1. Go to https://app.netlify.com/drop
2. Drag the entire `pokemonmonitor` folder onto the page
3. Netlify gives you a free URL like `https://amazing-name-123.netlify.app`
4. Open that URL on your iPhone

### Option B — GitHub Pages (free, permanent)
1. Create a free account at github.com
2. Click "New repository", name it `pokemonmonitor`, set to Public
3. Upload all files in this folder
4. Go to Settings → Pages → Source: main branch → Save
5. Your URL will be `https://yourusername.github.io/pokemonmonitor`

---

## Add to iPhone Home Screen

1. Open the URL in Safari (must be Safari, not Chrome)
2. Tap the Share button (box with arrow at bottom)
3. Tap "Add to Home Screen"
4. Name it "PC Monitor" → tap Add
5. It now appears as an app icon!

---

## Important note about background monitoring

Safari on iPhone pauses JavaScript when you switch apps.
This means the monitor only checks while the app is open on screen.

**To get true background alerts**, keep the screen on and the
app open while you're waiting for a drop — or consider leaving
a laptop/PC running the Python script version for background monitoring.

The app WILL send a notification if it detects a queue while open.
Make sure to tap Allow when it asks for notification permission!
