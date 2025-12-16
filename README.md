# Costing.sk — Moderná webstránka na GitHub Pages

Tento repozitár obsahuje zdrojový kód pre webstránku **Costing.sk**, určenú na prezentáciu služieb odhadu nákladov v stavebníctve.

## 📂 Štruktúra súborov
- `index.html` — hlavná stránka (one‑page dizajn)
- `style.css` — štýly pre všetky podstránky
- `about.html` — podstránka s detailnými informáciami o autorovi
- `contact.html` — podstránka s kontaktným formulárom
- `CNAME` — nastavenie vlastnej domény (`www.costing.sk`)
- `images/` — priečinok pre obrázky (hero, about, favicon)
- `README.md` — dokumentácia projektu

## 🚀 Nasadenie na GitHub Pages
1. Nahrajte všetky súbory do vetvy `main`.
2. V nastaveniach repozitára (`Settings → Pages`) nastavte zdroj:  
   - **Branch:** `main`  
   - **Folder:** `/ (root)`
3. Uistite sa, že v súbore `CNAME` je správna doména (`www.costing.sk` alebo `costing.sk`).
4. V DNS záznamoch nastavte:
   - **A záznamy root domény** → GitHub IP:  
     `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - **CNAME `www`** → `matko1985.github.io`
5. Po propagácii zapnite **Enforce HTTPS** v nastaveniach GitHub Pages.

## 🖥️ Funkcie stránky
- Moderný responzívny dizajn (desktop + mobil)
- Hero sekcia so sloganom a CTA
- Sekcia služieb s ikonami
- Sekcia „O mne“ s detailmi
- Referencie projektov
- Blog/Tipy sekcia
- Kontakt s formulárom, emailom, telefónom a mapou
- Jednotný dizajn pre podstránky (`about.html`, `contact.html`)

## ⚙️ Úpravy
- Farby a CTA sa menia v `:root` premenných v `style.css`.
- Obrázky nahraďte vlastnými v priečinku `images/`.
- Texty sekcií upravte priamo v `index.html`, `about.html`, `contact.html`.

## 📧 Kontakt
- Email: info@costing.sk  
- Telefón: +421 9XX XXX XXX  
- Lokalita: Košice, Slovensko
