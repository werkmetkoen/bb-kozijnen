# Backlog BB Kozijnen
*Laatst bijgewerkt: mei 2026*

## Gereed
- Eerste versie testsite gebouwd in Astro + Tailwind
- Live gezet op Netlify
- Logo SVG aangemaakt en verwerkt in navigatie
- Reviews en werkgebied (Utrechtse Heuvelrug e.o.) verwerkt
- Donker kleurenschema doorgevoerd
- Navigatie uitgebreid met vier hoofdcategorieën en dropdowns
- Partnerbalk toegevoegd (Unilux, Kömmerling, Smits Kozijnen, Smits Isolatieglas)
- Teksten van Marko verwerkt op homepage, over ons, isolatieglas, horren
- Huisstijl gesynchroniseerd met merkidentiteit Balfoort Bouw (antraciet + goud)
- tokens.css aangemaakt als centrale kleurenbeheer
- Huisstijl.md bijgewerkt en op GitHub gezet

## Wacht op Claude Code (bezig)
- Productpagina's aanmaken (23 pagina's gebouwd)
- Submenu links naar productpagina's
- Kleurstructuur via tokens.css volledig doorgevoerd

## Wacht op Marko
- Logo (in dezelfde stijl als busje)
- Domeinnaam bevestigen
- Foto's van uitgevoerde projecten
- Productinfo aluminium kozijnen
- Toestemming foto's schipperkozijnen.nl
- Akkoord op offerte

## Volgende stappen na akkoord Marko
- Offerte versturen (klaar als docx)
- Formspree activeren met echt formulier-ID
- Domein koppelen via Hostnet
- Eigen projectfoto's verwerken
- Google Ads campagne opzetten parallel aan bouw

## Technische werkregels
- Kleuren altijd via tokens.css, nooit hardcoded
- Commits na elke sessie naar GitHub
- Netlify update automatisch na elke push

## CSS-architectuur (mei 2026)

**Beslissing:** Eén centraal tokens.css bestand met alle kleuren 
en herbruikbare component-klassen.

**Werkregels:**
- Nooit kleurwaarden hardcoderen buiten tokens.css
- Nooit !important gebruiken — als het nodig is klopt de structuur niet
- Secties krijgen altijd section-dark, section-light of section-brown
- Knoppen altijd btn-primary of btn-secondary
- Kaarten altijd card-dark of card-light

**Reden:** Eerdere aanpak met losse fixes per component leidde tot 
inconsistente kleuren en conflicten. Dit systeem is schaalbaar — 
één aanpassing in tokens.css past de hele site aan.