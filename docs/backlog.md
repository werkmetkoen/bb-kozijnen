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
- Navigatie geherstructureerd — Producten dropdown met 4 items,
  Projecten, Over ons, Werkwijze, Offerte aanvragen
- Dropdown hover-fix via ::before brug — werkt stabiel op desktop
- Partnerbalk toegevoegd (Unilux, Kömmerling, Smits Kozijnen, 
  Smits Isolatieglas)
- Teksten van Marko verwerkt op homepage, over ons, 
  isolatieglas en horren
- 24 pagina's gebouwd inclusief alle productpagina's 
  en subcategorieën
- Mobiel hamburger menu gebouwd — logo links, hamburger rechts
- Playfair Display en Raleway geladen via Google Fonts
- CLAUDE.md aangemaakt als werkinstructiebestand
- Huisstijl gesynchroniseerd met merkidentiteit Balfoort Bouw
- GitHub template repository aangemaakt (astro-project-template)
- Kömmerling encoding definitief opgelost (UTF-8, alle bestanden)
- Sterren en streepjes encoding gefixed in reviews
- Breadcrumb verbeterd — subtiel, › scheidingsteken, 
  transparante achtergrond
- Label in hoofdletters verwijderd van 15 productpagina's
- Offerte opgesteld als Word-document (41 uur, €2.665 excl. BTW)
- Mail aan Marko gestuurd met testlink en samenvatting wensen

## Direct op te lossen bij volgende Claude Code sessie
- Placeholder foto's toevoegen op sleutelposities
  (homepage werkwijze, over ons, projectenpagina)
- Intro-teksten subpagina's controleren op leesbaarheid
- .gitattributes toevoegen voor line-ending consistentie

## Wacht op Marko
- Definitief logo (stijl busje)
- Domeinnaam bevestigen
- Foto's van uitgevoerde projecten — gevels, 
  kozijndetails, interieurs
- Foto van Marko zelf voor Over ons pagina
- Productinfo aluminium kozijnen
- Toestemming foto's schipperkozijnen.nl
- Akkoord op offerte (41 uur, €2.665 excl. BTW)
- Akkoord op scope (24 pagina's, vier productcategorieën)
- Reactie op bijgestelde offerte

## Volgende stappen na akkoord Marko
- Offerte versturen (klaar als docx)
- Formspree activeren met echt formulier-ID
- Domein koppelen via Hostnet
- Eigen projectfoto's verwerken
- Placeholder foto's vervangen door eigen materiaal
- Aluminium kozijnen pagina uitwerken met echte content
- Reviews koppelen aan Google
- Google Ads campagne opzetten parallel aan bouw

## Technische werkregels
- Kleuren altijd via tokens.css, nooit hardcoded
- Nooit !important gebruiken
- Commits na elke sessie naar GitHub
- Netlify update automatisch na elke push
- Copilot en Claude Code zitten beide in VS Code — 
  gebruik alleen Claude Code (sterretje-icoon)