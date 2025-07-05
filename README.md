# 🚀 Moderní Webová Stránka

Krásná, responzivní webová stránka s moderním designem a interaktivními prvky.

## ✨ Funkce

- 🎨 Moderní gradient design
- 📱 Plně responzivní (mobilní, tablet, desktop)
- ⚡ Rychlé načítání a plynulé animace
- 🎯 Smooth scroll navigace
- 📧 Funkční kontaktní formulář
- 🌟 Interaktivní prvky a hover efekty
- 📊 Intersection Observer animace
- 🎪 Parallax efekty

## 🛠️ Technologie

- **HTML5** - Sémantická struktura
- **CSS3** - Moderní styly, Grid, Flexbox, Animace
- **JavaScript (ES6+)** - Interaktivita a animace
- **Font Awesome** - Ikony
- **Google Fonts** - Typografie (Inter)

## 📁 Struktura souborů

```
├── index.html          # Hlavní HTML soubor
├── styles.css          # CSS styly
├── script.js           # JavaScript funkcionalita
└── README.md           # Tento soubor
```

## 🌐 Jak hostovat

### 1. GitHub Pages (Nejjednodušší - BEZPLATNÉ)

1. Vytvoř GitHub repository
2. Nahraj všechny soubory do repository
3. Jdi do Settings → Pages
4. Vyber Source: "Deploy from a branch"
5. Vyber branch: "main" a folder: "/ (root)"
6. Klikni "Save"
7. Tvůj web bude dostupný na: `https://tvojejmeno.github.io/nazev-repository`

### 2. Netlify (Drag & Drop - BEZPLATNÉ)

1. Jdi na [netlify.com](https://netlify.com)
2. Zaregistruj se nebo se přihlas
3. Přetáhni celou složku s webem do oblasti "Drag and drop your site output folder here"
4. Netlify automaticky nasadí tvůj web
5. Dostaneš URL adresu (např. `https://random-name.netlify.app`)

### 3. Vercel (Pro pokročilé - BEZPLATNÉ)

1. Jdi na [vercel.com](https://vercel.com)
2. Připoj GitHub účet
3. Importuj repository
4. Vercel automaticky nasadí web
5. Každý push do GitHub automaticky aktualizuje web

### 4. Firebase Hosting (Google - BEZPLATNÉ)

1. Nainstaluj Firebase CLI: `npm install -g firebase-tools`
2. Přihlas se: `firebase login`
3. Inicializuj projekt: `firebase init hosting`
4. Deploy: `firebase deploy`

### 5. VPS/Shared Hosting (PLACENÉ)

1. **VPS (DigitalOcean, AWS, Azure)**
   - Nahraj soubory přes FTP/SFTP
   - Nastav web server (Apache/Nginx)

2. **Shared Hosting (cPanel)**
   - Nahraj soubory do `public_html` složky
   - Web bude dostupný na tvé doméně

## 🎨 Přizpůsobení

### Změna barev
V `styles.css` najdi a uprav tyto CSS proměnné:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #ffd700;
}
```

### Změna textů
Uprav texty přímo v `index.html` souboru.

### Přidání nových sekcí
1. Přidej HTML strukturu do `index.html`
2. Přidej CSS styly do `styles.css`
3. Přidej JavaScript funkcionalitu do `script.js`

## 📱 Testování

- Otevři `index.html` v prohlížeči pro lokální testování
- Použij Developer Tools pro testování responzivity
- Testuj na různých zařízeních

## 🚀 Optimalizace pro produkci

1. **Minifikace souborů**
   - Použij nástroje jako UglifyJS pro JavaScript
   - Použij CSS minifier pro CSS

2. **Komprese obrázků**
   - Použij WebP formát
   - Optimalizuj velikost obrázků

3. **Caching**
   - Nastav správné cache headers
   - Použij CDN pro externí soubory

## 📞 Podpora

Pokud máš problémy s nasazením nebo chceš přidat nové funkce, vytvoř issue v GitHub repository nebo mě kontaktuj.

## 📄 Licence

Tento projekt je open source a dostupný pod MIT licencí.

---

**Vytvořeno s ❤️ pro moderní web** 