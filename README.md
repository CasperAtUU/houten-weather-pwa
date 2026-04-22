# Houten Weather — PWA Edition

A real-time weather app that works as a native app on your phone. Install it directly from your home screen.

## Features

✅ **Installable** — Add to home screen like a native app  
✅ **Works offline** — Service worker caches data  
✅ **Auto-updates** — Data refreshes every 10 minutes  
✅ **Real-time** — Current temp, condition, sunrise/sunset, rain forecast  
✅ **Zero backend** — Uses free Open-Meteo API  

## Files

- `index.html` — Main app (HTML + CSS + JS in one file)
- `manifest.json` — PWA metadata for home screen icon
- `service-worker.js` — Offline support + caching
- `.nojekyll` — Tell GitHub Pages not to process Jekyll

## Deploy on GitHub Pages

1. **Create a new GitHub repo** (e.g. `houten-weather-pwa`)

2. **Push these files to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial PWA release"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/houten-weather-pwa.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to repo **Settings** → **Pages**
   - Set **Source** to `main` branch, `/root` directory
   - Wait ~1 minute for deployment

4. **Your app is live!** Visit `https://YOUR_USERNAME.github.io/houten-weather-pwa`

## Install on Your Phone

**On Android (Poco X3):**

1. Open the app URL in Brave/Chrome
2. Tap the menu (⋮) → **"Install app"** (or "Add to Home Screen")
3. **Done!** Icon appears on your home screen

Click the icon anytime to open the app — works offline, auto-refreshes every 10 min.

## Local Testing

Just open `index.html` in your browser. Or:

```bash
# If you have Python 3:
python -m http.server 8000
# Visit http://localhost:8000
```

---

**Made with ❄️ for Houten, NL**

