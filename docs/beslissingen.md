## Technische keuzes
- Framework: Astro + Tailwind CSS als basis, kleuren volledig beheerd via tokens.css (geen WordPress — klant beheert nooit zelf content)
- Hosting: Netlify (gratis, automatische deployment vanuit GitHub)
- Formulieren: Formspree (nog te activeren)
- Domein en e-mail: Hostnet (zelfde als balfoortbouw.nl)
- Geen CMS — overbodig voor deze klant

## Businesskeuzes
- Koen bouwt zelf ipv uitbesteden aan Myra (Sites & Search)
- Foto's van schipperkozijnen.nl als placeholder — toestemming nog nodig
- Werkgebied: Utrechtse Heuvelrug, Utrecht, De Meern, Veenendaal en omstreken
- Referentiesite: ekkozijnen.nl — structuur en diepgang als richtlijn
- Scope uitgebreid van 8 naar 23 pagina's na input Marko (mei 2026)
- Offerte bijgesteld: 41 uur, €2.665 excl. BTW

## Typografie (mei 2026)
- Logo naam: Raleway bold — strak, sans-serif, 
  zoals bedrijfsnaam op busje
- Logo tagline: Playfair Display italic — elegant, 
  zoals "Kwaliteit zit in details" op busje
- H1 koppen: Playfair Display serif
- Navigatie en labels: Raleway, gespatieerd
- Reden: directe vertaling van merkidentiteit busje 
  naar website

## Kleurpalet update (mei 2026)
- --c-dark aangepast van #222222 naar #1e1a17
  (warmere antraciet met bruinige ondertoon)
- --c-accent aangepast van #c8922a naar #b07535
  (warmere bronzige goudtint dichter bij busje)
- Reden: nauwkeurigere match met bestaande 
  merkidentiteit Balfoort Bouw

  ## CSS-architectuur (mei 2026)
- Eén centraal tokens.css bestand met alle kleuren 
  en herbruikbare component-klassen
- Werkregels:
  - Nooit kleurwaarden hardcoderen buiten tokens.css
  - Nooit !important gebruiken
  - Secties: altijd section-dark, section-light of section-brown
  - Knoppen: altijd btn-primary of btn-secondary
  - Kaarten: altijd card-dark of card-light
- Reden: eerdere aanpak met losse fixes per component leidde 
  tot inconsistente kleuren en conflicten