# Study Planner PWA

A mobile-first study planner with subject timers, alarm scheduling, and progress charts — installable as an Android/iOS app via PWA.

## 📁 Files

```
/
├── index.html          ← The full app (edited for PWA)
├── manifest.json       ← Web App Manifest
├── sw.js               ← Service Worker (offline support)
└── icons/
    ├── icon-72x72.png
    ├── icon-96x96.png
    ├── icon-128x128.png
    ├── icon-144x144.png
    ├── icon-152x152.png
    ├── icon-192x192.png
    ├── icon-384x384.png
    ├── icon-512x512.png
    └── maskable-icon-192x192.png
```

## 🚀 Deploy to GitHub Pages (3 steps)

1. **Create a new GitHub repo** (public)
2. **Upload all files** keeping the folder structure above
3. Go to **Settings → Pages → Source → main branch → / (root)** → Save

Your app will be live at:
`https://<your-username>.github.io/<repo-name>/`

## 📱 Install on Android

1. Open the GitHub Pages URL in **Chrome**
2. Tap the **⋮ menu → "Add to Home screen"**
3. Tap **Install** — it'll appear as an app icon on your home screen

Works fully offline after first load.

## Features

- ⏱ Per-subject study timers (only one runs at a time)
- 📊 Bar chart + donut chart of study time
- 🔔 Alarm scheduler with daily/weekday/weekend/once options
- 💾 All data saved locally in the browser (localStorage)
- 📴 Offline-capable via service worker
