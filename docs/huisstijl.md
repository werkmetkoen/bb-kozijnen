# Huisstijl BB Kozijnen
*Laatst bijgewerkt: mei 2026*

## Merkidentiteit
De huisstijl is gebaseerd op de bestaande merkidentiteit van Balfoort Bouw —
warm, donker en aards. Referentie: het busje van het bedrijf (antraciet met
goudaccenten). De site sluit hierop aan in plaats van een generiek bouwbedrijf-
blauw te gebruiken.

---

## Kleurenpalet

Alle kleuren worden beheerd via `/src/styles/tokens.css`.
**Werkregel: nooit een kleurwaarde hardcoderen buiten tokens.css. Altijd via variabelen.**

| Variabele              | Hexwaarde   | Gebruik                                      |
|------------------------|-------------|----------------------------------------------|
| --color-bg-dark        | #222222     | Hoofdachtergrond donkere secties             |
| --color-bg-darker      | #1a1a1a     | Navigatiebalk, footer                        |
| --color-bg-brown       | #3d2b1f     | Accentsecties, partners balk                 |
| --color-bg-light       | #f5f0e8     | Lichte secties (warm gebroken wit)           |
| --color-bg-white       | #ffffff     | Kaarten op lichte achtergrond                |
| --color-accent         | #c8922a     | Knoppen, labels, highlights, logo tekst      |
| --color-accent-hover   | #a8741a     | Hover staat knoppen                          |
| --color-text-light     | #ffffff     | Alle tekst op donkere achtergrond            |
| --color-text-cream     | #e0d5c5     | Subtekst op donkere achtergrond              |
| --color-text-dark      | #1e1e1e     | Koppen op lichte achtergrond                 |
| --color-text-grey      | #555555     | Body tekst op lichte achtergrond             |
| --color-nav-bg         | #1a1a1a     | Navigatiebalk achtergrond                    |
| --color-nav-text       | #ffffff     | Navigatietekst                               |
| --color-card-bg        | #2e2e2e     | Kaarten op donkere achtergrond               |
| --color-border-accent  | rgba(200,146,42,0.2) | Subtiele gouden rand op kaarten    |

---

## Typografie

- **Logo en H1 koppen**: Playfair Display, italic (Google Font)
  — aansluitend bij het schreefletter op het busje
- **Navigatie en body tekst**: sans-serif (systeemlettertype)
- **Koppen op donker**: --color-text-light (#ffffff)
- **Labels (gespatieerd)**: --color-accent (#c8922a), letter-spacing: 0.1em,
  uppercase
- **Broodtekst op donker**: --color-text-cream (#e0d5c5)
- **Broodtekst op licht**: --color-text-grey (#555555)

---

## Logo

- Horizontaal: `/src/assets/logo.svg`
- Gestapeld: `/src/assets/logo-stacked.svg`
- Icoon: gestileerd kozijnraster
- Logokleur: --color-accent (#c8922a) voor icoon en naam
- Ondertitel: --color-text-cream, klein, gespatieerd

---

## Sectieopbouw homepage

Secties wisselen in deze volgorde van achtergrond:
1. Navigatie: --color-bg-darker
2. Hero: --color-bg-dark
3. Voordelen: --color-bg-light
4. Producten/diensten: --color-bg-dark
5. Werkwijze: --color-bg-light
6. Duurzaamheid: --color-bg-brown
7. Partners: --color-bg-brown
8. Reviews: --color-bg-dark
9. CTA: --color-bg-darker
10. Footer: --color-bg-darker

---

## Knoppen

| Type           | Achtergrond       | Tekst              | Hover              |
|----------------|-------------------|--------------------|--------------------|
| Primair        | --color-accent    | #ffffff            | --color-accent-hover |
| Secundair      | transparant       | --color-accent     | --color-accent (bg), #fff (tekst) |
| Navigatie CTA  | --color-accent    | #ffffff            | --color-accent-hover |

---

## Tone of voice

- Vakkundig maar toegankelijk
- Gericht op particulieren in de regio Utrechtse Heuvelrug, Utrecht,
  De Meern, Veenendaal en omstreken
- Lokaal en persoonlijk — Marko en zijn team, geen anoniem bedrijf
- Betrouwbaar en no-nonsense
- U-vorm (formeel maar niet afstandelijk)

---

## Referenties

- Structuur en diepgang: ekkozijnen.nl
- Merkidentiteit en sfeer: busje Balfoort Bouw (antraciet + goud)
- Leveranciers voor beeldmateriaal: schipperkozijnen.nl (toestemming nodig)