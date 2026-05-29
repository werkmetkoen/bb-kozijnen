# BB Kozijnen — Werkinstructies voor Claude Code

## Project
Website voor BB Kozijnen (Balfoort Bouw), gebouwd in Astro + Tailwind CSS.
GitHub: werkmetkoen/bb-kozijnen
Live: Netlify (automatische deployment via GitHub)

## Technische werkregels

### CSS en kleuren
- Alle kleuren staan in /src/styles/tokens.css — nergens anders
- Nooit kleurwaarden hardcoderen buiten tokens.css
- Nooit !important gebruiken — als het nodig is klopt de structuur niet
- Secties: altijd class section-dark, section-light of section-brown
- Knoppen: altijd class btn-primary of btn-secondary
- Kaarten: altijd class card-dark of card-light

### Code
- Nooit inline stijlen schrijven
- Componentbestanden bevatten geen kleurdefinities
- Na elke wijziging valideren met npm run build

### Git
- Na elke sessie committen en pushen naar GitHub
- Commit-omschrijvingen in het Nederlands
- Documentatie bijwerken in /docs bij elke structuurwijziging

## Documentatie
- /docs/backlog.md — openstaande taken en status
- /docs/huisstijl.md — kleuren, typografie, merkidentiteit
- /docs/beslissingen.md — waarom technische keuzes zijn gemaakt
- /docs/afspraken.md — klantafspraken en openstaande punten

## Klant
- Naam: Marko Balfoort
- Bedrijf: Balfoort Bouw / BB Kozijnen
- Werkgebied: Utrechtse Heuvelrug, Utrecht, De Meern, Veenendaal
- Leverancier kozijnen: schipperkozijnen.nl
- Referentiesite: ekkozijnen.nl

## Huisstijl samenvatting
- Primaire kleur: antraciet #222222 (warm, gebaseerd op bedrijfsbusje)
- Accent: goud #c8922a
- Donkerbruin accent: #3d2b1f
- Lichte achtergrond: #f5f0e8 (warm gebroken wit)
- Logo: Playfair Display italic, goudkleur
- Tone of voice: vakkundig, toegankelijk, lokaal, u-vorm