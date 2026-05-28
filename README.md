# BB Kunststof Kozijnen

Website voor BB Kunststof Kozijnen, een Nederlands installatiebedrijf voor kunststof kozijnen.

## Project inhoud

- Astro-project met Tailwind CSS
- Nederlandse website voor particulieren
- Homepage, 4 productpagina’s (Cube, Trend, Classic, City)
- Werkwijze, Over ons en Offerte aanvragen
- Formspree-offerteformulier met placeholder-endpoint
- Netlify deploymentconfiguratie via `netlify.toml`

## Lokaal draaien

1. Installeer dependencies:

```sh
npm install
```

2. Start de ontwikkelserver:

```sh
npm run dev
```

3. Open de site in je browser:

```sh
http://localhost:4173
```

4. Om een productiebuild te maken:

```sh
npm run build
```

5. Om de build lokaal te bekijken:

```sh
npm run preview
```

## Netlify deployment

- `netlify.toml` publiceert de `dist`-map
- `npm run build` is het build-commando
- Het formulier gebruikt een placeholder Formspree-endpoint: vervang `https://formspree.io/f/your-form-id` met je eigen ID
