# 🏝️ Animal Crossing: Wild World Checklist

A cozy, lightweight **progress checklist web app** for **Animal Crossing: Wild World** collectors.
Track your furniture, clothes, museum progress, and more — all in one place, even **offline**.

Built as a fast, installable **Progressive Web App (PWA)** with a soft Animal Crossing–inspired design 🌱

---

## ✨ Features

* 📋 **Complete item checklists**
  Furniture, clothes, accessories, umbrellas, wallpapers, carpets, gyroids, songs, photos, museum, bugs, and fish.

* ✅ **Progress tracking**

  * Overall completion percentage
  * Per-category progress bars
  * Live updates as you check items

* 🔍 **Search & filters**

  * Instant search
  * Filter by *All*, *Obtained*, or *Not Obtained*

* 🌗 **Light & Dark Mode**

  * Toggle anytime
  * Theme preference persists

* 📱 **PWA support**

  * Installable on mobile & desktop
  * Works offline via service worker caching

* ⚡ **Fast & simple**

  * No frameworks
  * Pure HTML, CSS, and JavaScript

---

## 🧱 Tech Stack

* **HTML5**
* **CSS3** (CSS variables for theming)
* **Vanilla JavaScript**
* **Service Workers** (offline support)
* **Web App Manifest** (PWA install)

---

## 📂 Project Structure

```text
.
├── index.html          # Main app layout
├── style.css           # UI styling & themes
├── script.js           # App logic & data
├── manifest.json       # PWA configuration
├── service-worker.js   # Offline caching
├── header.webp         # App header image
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ravionry/acww.check.git
cd acww.check
```

### 2. Open locally

Just open `index.html` in your browser — no build step required.

### 3. (Optional) Install as an app

* Open in Chrome / Edge / mobile browser
* Use **“Add to Home Screen”** or **“Install App”**

---

## 📶 Offline Support

This app caches essential files on first load:

* `index.html`
* `style.css`
* `script.js`
* `manifest.json`

Once loaded, it works **fully offline** 🎉

---

## 🎨 Customization

You can easily tweak the look and feel via CSS variables:

```css
:root {
  --bg: #fffbe8;
  --accent: #7fb77e;
  --text: #3a3a3a;
}
```

Want to add more categories or items?
Just extend the data arrays in `script.js`.

---

## ⚠️ Disclaimer

This is a **fan-made project**.
Animal Crossing and related assets are © Nintendo.

---

## 💚 Credits

Special thanks to Mogchamp for making their checklist sheets publicly available. You can view here:
https://docs.google.com/spreadsheets/d/1DBaXMK5tnGEkbDk_VVmQDRNyd1Y3bv6l2wIJPreoHBM/copy

Made with love for fellow Wild World completionists 🌿

---
