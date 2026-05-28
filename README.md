# 🎨 ChromaCraft

> A Progressive Web App (PWA) demonstrating dynamic text colour changes .

---

## 📌 About

ChromaCraft is a 3-page Progressive Web App built with HTML, CSS and JavaScript. Users enter their name, select a text colour, and see their name rendered in that colour. The app is fully installable on Android devices directly from the browser — no app store needed.

---

## ✨ Features

- 3-page layout with shared Menu and Contents divisions
- Text colour selection — Black, Green, Yellow, Blue
- PWA — installable on Android as a home screen app
- Fully offline — works without internet after first load
- Responsive design with light pink theme
- No server needed — pure HTML, CSS & JavaScript

---

## 📁 File Structure

```
chromacraft/
├── index.html          # Home Page
├── textcolour.html     # Text Colour Selection Page
├── result.html         # Result Page (shows name in chosen colour)
├── styles.css          # Shared stylesheet for all 3 pages
├── manifest.json       # PWA manifest (enables installation)
├── sw.js               # Service Worker (offline support)
└── icons/
    ├── icon-192.png    # App icon (192x192)
    └── icon-512.png    # App icon (512x512)
```

---

## 🚀 How to Use

### Step 1 — Host on GitHub Pages
1. Create a new public repository named `chromacraft`
2. Upload all project files to the repository root
3. Go to **Settings → Pages → Deploy from main branch**
4. Your site will be live at:
   ```
   https://YOUR-USERNAME.github.io/chromacraft/
   ```

### Step 2 — Install on Android
1. Open the GitHub Pages URL in **Chrome** on your Android phone
2. Tap the **3-dot menu** (top right)
3. Tap **"Add to Home screen"** or **"Install app"**
4. ChromaCraft will appear on your home screen like a native app 🎉

### Step 3 — Use the App
1. **Page 1 (Home)** — Read the intro and click *Try it now*
2. **Page 2 (Colour Selection)** — Enter your name, choose a colour, tap **SUBMIT**
3. **Page 3 (Result)** — See your name displayed in the chosen colour

---

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and layout |
| CSS3 | Styling, layout, Google Fonts |
| JavaScript (ES6) | Form handling, sessionStorage, routing |
| Web App Manifest | PWA installation support |
| Service Worker | Offline caching |

---

## 📝 Notes

- The original assignment used JSP for the result page. In this PWA version, `sessionStorage` replaces JSP so the app works in any browser without a server.
- The background colour is light pink (`#ffe4ec`) as required by the assignment.
- The app caches all files on first load and works fully offline after that.

---

## 📚 Assignment Info

| Field | Details |
|---|---|
| Course | BCSL-057 — Web Technologies Lab |
| Assignment | Web Assignment 6 |
| University | IGNOU |

---

<p align="center">Made with ❤️ | ChromaCraft</p>
