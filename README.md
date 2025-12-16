# Costing.sk — GitHub Pages

Moderná, responzívna stránka pre odhad nákladov v stavebníctve.

## Súbory
- `index.html` — hlavná stránka (one‑page)
- `style.css` — štýly
- `images/` — sem vložte vlastné obrázky (`hero.jpg`, `about.jpg`, `favicon.png`)

## Nasadenie
1. Nahrajte súbory do `main` branch na GitHube.
2. V `Settings → Pages` nastavte zdroj `Deploy from a branch` → `main` → `/ (root)`.
3. V `CNAME` súbore ponechajte `www.costing.sk` (alebo zmeňte na `costing.sk` podľa preferencie).
4. V DNS:
   - A záznamy root domény na GitHub IP: 185.199.108.153 / .109.153 / .110.153 / .111.153
   - CNAME `www` → `matko1985.github.io`
5. Po propagácii zapnite **Enforce HTTPS** v `Settings → Pages`.

## Kontakt formulár
- Ak chcete, aby formulár odosielal emaily, zmeňte `action="#"` na URL poskytovateľa formulárov (alebo použite vlastný backend).
- Pridajte texty GDPR podľa potreby.

## Úpravy
- Farby a CTA zmeníte v `:root` premenných v `style.css`.
- Obrázky nahraďte vlastnými v priečinku `images/`.
- Sekcie upravte priamo v `index.html`.
