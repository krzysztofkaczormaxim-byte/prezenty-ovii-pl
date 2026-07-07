# prezenty.ovii.pl

Strona B2B destylarni OVII — prezenty biznesowe z personalizacją.

## Struktura

- `index.html` — landing page (publiczny)
- `kalkulator.html` — kalkulator paczek B2B (ukryty, noindex)
- `generator-listow.html` — generator listów "od serca" (ukryty, noindex)
- `one-pager.html` — one-pager A4 dla prezesów (ukryty, noindex)
- `CNAME` — domena niestandardowa dla GitHub Pages

## Publikacja

Hosting: GitHub Pages (branch `main`, katalog `/`).
DNS: rekord CNAME `prezenty.ovii.pl` → `<użytkownik>.github.io` w panelu seohost.

## Uwagi

- Formularz kontaktowy na landingu używa `mailto:` — docelowo podłączyć backend/narzędzie formularzy (np. Formspree).
- Placeholdery zdjęć na landingu (`.photo`) do podmiany na docelowe fotografie.
