# 🚀 HealthHub PWA — GitHub Pages Deploy Guide

## 📁 Files Jo Upload Karni Hain

```
healthhub-app/
├── index.html        ← (healthhub_pwa.html rename karke)
├── manifest.json
├── sw.js
├── icon-192.png
└── icon-512.png
```

---

## ✅ Step-by-Step Guide

### Step 1 — GitHub Account
- https://github.com pe signup karo (free hai)

### Step 2 — New Repository Banao
1. GitHub pe click karo **"New"** (green button, top left)
2. Repository name: `healthhub-app`
3. **Public** select karo ✅
4. **"Create repository"** click karo

### Step 3 — Files Upload Karo
1. Repository page pe **"uploading an existing file"** link click karo
2. Saari 5 files drag & drop karo:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. **"Commit changes"** click karo

### Step 4 — GitHub Pages Enable Karo
1. Repository mein **Settings** tab click karo
2. Left sidebar mein **Pages** click karo
3. **Source** dropdown mein `Deploy from a branch` select karo
4. **Branch** mein `main` select karo, folder `/root` rakho
5. **Save** click karo

### Step 5 — App URL Milega
2-3 minute baad tumhara app live hoga:
```
https://YOUR-USERNAME.github.io/healthhub-app/
```

---

## 📱 Phone Pe Install Kaise Karein

### Android (Chrome):
1. App URL Chrome mein kholo
2. 3-dot menu → **"Add to Home screen"**
3. Ya app khud install banner dikhayega → **"Install"** tap karo

### iPhone (Safari):
1. App URL Safari mein kholo
2. Share button (bottom) → **"Add to Home Screen"**
3. **"Add"** tap karo

### Desktop (Chrome/Edge):
1. Address bar mein right side install icon dikhega
2. Click karo → **"Install"**

---

## 🔧 Important Notes

- `healthhub_pwa.html` ko **rename** karke `index.html` karo
- GitHub Pages pe HTTPS automatic hai — PWA perfectly kaam karega
- Service Worker offline caching enable karega
- Install prompt automatic aayega 4 seconds baad

---

## 🎉 Done!
App install hone ke baad:
- Home screen pe HealthHub icon hoga
- Full screen khulega (browser bar nahi)
- Offline bhi data save hoga
- AI chat kaam karega (internet chahiye sirf AI ke liye)
