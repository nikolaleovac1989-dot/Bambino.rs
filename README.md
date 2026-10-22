# Bambino – frizersko-kozmetički salon, Jagodina

Jednostranični sajt salona Bambino (27. mart 43, Jagodina).

## Objavljivanje na GitHub Pages
1. Postavite sve fajlove iz ovog foldera u koren repozitorijuma.
2. Na GitHub-u otvorite **Settings → Pages**, izaberite granu `main` i folder `/ (root)`, pa sačuvajte.
3. Posle minut-dva sajt je dostupan na adresi koju GitHub prikaže.

## Pre objave
- U `index.html`, `robots.txt` i `sitemap.xml` zamenite `VAS-DOMEN.rs` pravim domenom.
- Instagram link unesite u `KONTAKT.instagram` (na vrhu skripte u `index.html`).
- WhatsApp/Viber brojeve proverite sa vlasnicom i po potrebi izmenite u `KONTAKT.kanali`.
- Fotografije radova dodajte u `USLUGE[...].radovi`, npr. `{ src: 'assets/radovi/manikir-1.webp', alt: 'Opis' }`.

## Struktura
- `index.html` – ceo sajt (HTML, CSS i JS)
- `assets/` – logo, slike i ikonice
- `favicon.ico`, `robots.txt`, `sitemap.xml`
- `.nojekyll` – GitHub Pages servira fajlove bez obrade
