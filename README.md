# 🎁 Vasilisa Birthday Card / Vasilin Poklon

Interaktivna čestitka za rođendan sa galerijom slika i poklonom koji iskače.

## 🌐 GitHub Pages (Potrebna Konfiguracija)

Čestitka je spremljena za GitHub Pages, ali je potrebna ručna konfiguracija:

### ⚙️ Kako omogućiti GitHub Pages

1. **Otvorite Settings repository-ja:**
   - Idite na: https://github.com/nadja1908/vasilisapoklon/settings

2. **Konfigurirajte Pages:**
   - Kliknutet na "Pages" u levoj navigaciji
   - Pod "Source", izaberite **"Deploy from a branch"**
   - Izaberite branch: **main**
   - Izaberite folder: **/ (root)**
   - Kliknutet "Save"

3. **Čekajte deployment:**
   - GitHub Actions će automatski deployovati čestitku
   - Obično traje 1-2 minuta
   - Site će biti dostupan na: **https://nadja1908.github.io/vasilisapoklon/**

## ✨ Karakteristike

- Mobilno-prilagođen dizajn
- Gallerija sa 4 slike
- Interaktivni poklon koji se otvara klikom na dugme
- Lepršaća animacija za slike
- Elegantna, topla boja paleta

## 📱 Kako koristiti

1. Otvori čestitku (nakon što je GitHub Pages konfiguriran)
2. Klikni na dugme "KLIKNI OVDE 🎁"
3. Poklon se otvara u iskačućem prozoru

## 🖥️ Lokalno testiranje

Jednostavno otvorite `index.html` u vašem pregledniku:
```
file:///C:/Users/djord/cestitka/index.html
```

## 🛠️ Tehnologija

- HTML5
- CSS3 (Grid, Flexbox, Animations)
- Vanilla JavaScript
- Responsive Design
- GitHub Actions (Automated Deployment)

## 📁 Struktura

```
.
├── index.html              # Glavna stranica
├── docs/                   # GitHub Pages folder (kopija)
│   └── index.html
├── public/
│   ├── IMG_5889.PNG        # Slika 1
│   ├── IMG_5890.PNG        # Slika 2
│   ├── IMG_5891.PNG        # Slika 3
│   ├── IMG_5892.PNG        # Slika 4
│   └── poklon.jpg          # Poklon slika
└── .github/workflows/
    └── pages.yml           # GitHub Actions workflow
```

## 🚀 Deployment

Svaki push na `main` branch će automatski deployovati čestitku na GitHub Pages putem GitHub Actions workflow-a.

---

Srećan rođendan, Vasilisa! 🎉✨
