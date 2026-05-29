# Backlog BB Kozijnen
*Laatst bijgewerkt: mei 2026*

## Gereed
- Eerste versie testsite gebouwd in Astro + Tailwind
- Live gezet op Netlify
- Logo SVG aangemaakt — Raleway bold voor naam, 
  Playfair Display italic voor tagline
- Reviews en werkgebied (Utrechtse Heuvelrug e.o.) verwerkt
- Donker kleurenpalet doorgevoerd op basis van busje Balfoort Bouw
- tokens.css aangemaakt als centrale kleurenbeheer
- CSS volledig gerefactored — section-dark/light/brown, 
  btn-primary/secondary, card-dark/light
- Navigatie uitgebreid met vier hoofdcategorieën en dropdowns
- Partnerbalk toegevoegd (Unilux, Kömmerling, Smits Kozijnen, 
  Smits Isolatieglas)
- Teksten van Marko verwerkt op homepage, over ons, 
  isolatieglas en horren
- 23 pagina's gebouwd inclusief alle productpagina's 
  en subcategorieën
- Mobiel hamburger menu gebouwd
- Playfair Display en Raleway geladen via Google Fonts
- CLAUDE.md aangemaakt als werkinstructiebestand
- Huisstijl gesynchroniseerd met merkidentiteit Balfoort Bouw
- GitHub template repository concept uitgewerkt

## Direct op te lossen bij volgende Claude Code sessie
- Kömmerling encoding gefixed (K♦mmerling → Kömmerling) 
  in index.astro (5 gevallen)
- Placeholder foto's toevoegen op sleutelposities 
  (homepage werkwijze, over ons, projectenpagina)
- Desktop dropdown fix — menu verdwijnt bij bewegen 
  naar submenu
- Intro-teksten subpagina's controleren op leesbaarheid

## Wacht op Marko
- Logo in stijl van busje (definitief)
- Domeinnaam bevestigen
- Foto's van uitgevoerde projecten — gevels, 
  kozijndetails, interieurs
- Foto van Marko zelf voor Over ons pagina
- Productinfo aluminium kozijnen
- Toestemming foto's schipperkozijnen.nl
- Akkoord op offerte
- Reactie op bijgestelde offerte
- Bevestiging scope (23 pagina's akkoord?)

## Volgende stappen na akkoord Marko
- Offerte versturen (klaar als docx)
- Formspree activeren met echt formulier-ID
- Domein koppelen via Hostnet
- Eigen projectfoto's verwerken
- Google Ads campagne opzetten parallel aan bouw
- Placeholder foto's vervangen door eigen materiaal
- Alumni kozijnen pagina uitwerken met echte content
- Reviews koppelen aan Google (Marko heeft Google reviews)

## Technische werkregels
- Kleuren altijd via tokens.css, nooit hardcoded
- Nooit !important gebruiken
- Commits na elke sessie naar GitHub
- Netlify update automatisch na elke push