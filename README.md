# Launcher: your own address + phone icon

This folder is a tiny website. It shows the icon and opens the private app on claude.ai.
Nothing private is in it: no lessons, no audio, no work phrases. The app itself stays private on Claude.

Files: `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `maskable-512.png`, `apple-touch-icon.png`.

## Put it online (free, about 5 minutes, on the PC)

1. Go to https://github.com/signup and create a free account. The username becomes your address.
   Example: username `dan-italiano` gives `https://dan-italiano.github.io`.
2. Top right **+** → **New repository**.
   - Repository name: exactly `USERNAME.github.io` (your username, e.g. `dan-italiano.github.io`).
   - Public, tick nothing else → **Create repository**.
3. On the new page click **uploading an existing file**. Drag in **all the files of this folder** (not the folder itself), except this README if you like. Click **Commit changes**.
4. Wait 1–2 minutes, then open `https://USERNAME.github.io` in Chrome on the phone.
5. Chrome menu **⋮** → **Install app** (or **Add to Home screen**). The notebook icon appears on your home screen.

Tapping the icon opens the app. If the microphone or voice doesn't work, use the **Apri in Chrome** button on the launcher.

## Later
- A real domain (e.g. `italianoperdan.it`, about €10 a year): buy it, then in the repository **Settings → Pages → Custom domain**. Ask Claude to walk you through the DNS step.
- If the app's link ever changes, edit the two links in `index.html`.
