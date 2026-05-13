# 🇩🇪 Deutsch Grammatik — گرامر آلمانی

یک Progressive Web App (PWA) برای یادگیری گرامر آلمانی به فارسی.  
کاملاً آفلاین، رایگان، و قابل نصب روی iPhone و Android.

---

## ✅ PWA Checklist

| قابلیت | وضعیت |
|--------|--------|
| `index.html` کامل | ✅ |
| سازگار با GitHub Pages | ✅ |
| `manifest.json` کامل | ✅ |
| Service Worker + Offline Cache | ✅ |
| Update Notification | ✅ |
| نصب روی iPhone | ✅ |
| Fullscreen بدون نوار | ✅ |
| Apple Touch Icon (همه سایزها) | ✅ |
| Favicon (SVG) | ✅ |
| آیکون تمام سایزها (72→512) | ✅ |
| Splash Screen meta tags | ✅ |
| Dark Mode + Light Mode | ✅ |
| Responsive (موبایل + دسکتاپ) | ✅ |
| مسیر Relative | ✅ |
| Open Graph / Twitter Card | ✅ |
| JSON-LD Structured Data | ✅ |
| `robots.txt` + `sitemap.xml` | ✅ |
| صفحه `404.html` | ✅ |
| Android Install Prompt | ✅ |
| آفلاین Badge | ✅ |
| Safe Area (iPhone notch) | ✅ |
| Navigation بین صفحات | ✅ |

---

## 📚 درس‌ها

| # | درس | سطح | وضعیت |
|---|-----|-----|--------|
| ۱ | **Perfekt** — زمان گذشته کامل | A2 + B1/B2 | ✅ آماده |
| ۲ | **Präteritum** | A2 | 🔜 به زودی |
| ۳ | **Modalverben** | A2 | 🔜 به زودی |
| ۴ | **Trennbare Verben** | A2 | 🔜 به زودی |
| ۵ | **Komparativ & Superlativ** | A2 | 🔜 به زودی |
| ۶ | **Wechselpräpositionen** | A2 | 🔜 به زودی |
| ۷ | **Nebensätze** | A2 | 🔜 به زودی |
| ۸ | **Dativ** | A2 | 🔜 به زودی |

---

## 📁 ساختار پروژه

```
deutsch-grammar/
├── index.html            ← صفحه اصلی
├── manifest.json         ← تنظیمات PWA
├── sw.js                 ← Service Worker
├── favicon.svg           ← Favicon
├── robots.txt            ← SEO
├── sitemap.xml           ← SEO
├── 404.html              ← صفحه خطا
├── icons/
│   ├── apple-touch-icon.png
│   ├── icon-72.png
│   ├── icon-96.png
│   ├── icon-120.png
│   ├── icon-128.png
│   ├── icon-144.png
│   ├── icon-152.png
│   ├── icon-180.png
│   ├── icon-192.png
│   ├── icon-384.png
│   └── icon-512.png
└── lessons/
    ├── perfekt.html      ← درس ۱
    └── ...
```

---

## 🚀 انتشار روی GitHub Pages

1. این repo را Fork کن
2. برو **Settings → Pages**
3. زیر **Branch** گزینه `main` و `/ (root)` را انتخاب کن
4. روی **Save** بزن

آدرس:
```
https://[username].github.io/deutsch-grammar
```

> **نکته:** بعد از انتشار، `USERNAME` را در `robots.txt`، `sitemap.xml`، و meta tag های `og:url` با نام کاربری GitHub خودت جایگزین کن.

---

## 📱 نصب روی گوشی

**iPhone (Safari):**  
Share → Add to Home Screen → Add

**Android (Chrome):**  
منوی سه‌نقطه → Add to Home Screen

---

## 🛠 اضافه کردن درس جدید

1. فایل HTML را در `lessons/` بساز
2. لینک آن را در `index.html` اضافه کن
3. مسیر آن را در آرایه `PRECACHE` داخل `sw.js` اضافه کن
4. در `sitemap.xml` یک `<url>` جدید اضافه کن

---

ساخته شده با ❤️ برای یادگیری آلمانی · آفلاین و رایگان
