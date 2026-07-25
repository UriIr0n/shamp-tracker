# שמפ — אפליקציית מעקב פוריות

PWA (Progressive Web App) למעקב מחזור ופוריות. אפליקציה סטטית ב-HTML/JS, ללא backend.

## Stack

- Frontend: HTML5 + CSS + Vanilla JS
- גרפים: Chart.js CDN
- PWA: manifest.json + service worker (sw.js)
- שפה: עברית, RTL

## קבצים מרכזיים

- `index.html` — האפליקציה כולה (single file)
- `manifest.json` — הגדרות PWA
- `sw.js` — service worker לעבודה offline
- `icon-192.png`, `icon-512.png` — אייקונים

## הרצה

פתח `index.html` בדפדפן, או הגש דרך שרת סטטי:
```bash
python -m http.server 8080
```

## התקנה כ-PWA

ניתן להתקין על מסך הבית של Android/iPhone מהדפדפן.

## הערות

- `ziRM96A5`, `ziptdquG` — קבצי zip ארעיים, ניתן למחוק
- `pwa-mobile-app.skill` — skill להתקנה ב-Cowork (Settings → Capabilities)
- `fertility-app.zip` — גרסת ארכיון של האפליקציה
