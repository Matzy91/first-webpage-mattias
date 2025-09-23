# Bootcamp FMW2025 - 🧱 Introduktion till HTML

Vid bootcampens slut kommer ni ha byggt en statisk multi-page application - En webbsida innehållande flera sidor. Denna vecka ska vi fokusera på HTML. Webbsidans "byggstenar" eller "skelett".

## 🧾 Sidan ska innehålla

- En rubrik - `<h1>`, `<h2>` etc.
- Text - en paragraf med "Lorem ipsum..." duger
- En `<nav>` bar med två länkar/knappar
  - En hem-knapp som leder till huvudsidan
  - En kontakt-knapp som leder till ett kontaktformulär
- En kontaktsida med ett formulär, en `<input type="text">` och en `<button type="submit">`
- En eller flera bilder

## 🎨 Välj ut en design

För att lista ut vilka HTML-element sidan ska bestå av är det hjälpsamt att ha en design (s.k. mock-up) eller skiss redo. Här har ni fria händer. Det är helt upp till er om ni vill skissa fram en design från grunden eller använda en redan existerande från sidor som [dribbble.com](https://dribbble.com/) eller liknande, så länge den innehåller punkterna som listas ovan.

### Exempel på mock-ups

- [Citat-UI 1](https://dribbble.com/shots/3962634-Author-Quote-UI-Challenge)
- [Citat-UI 2](https://dribbble.com/shots/1492537-Adobe-Fireworks-Quote-UI-Freebie-Steve-Jobs)
- [Supported countries](https://dribbble.com/shots/25977317-Supported-Countries)

#### Exempel från ämnesklippet

<img src="exempel1.png" width="400">

<img src="exempel2.png" width="400">

## 🕵️‍♀️ Analysera designen

När ni valt design kan ni börja analysera vilka element den består av och hur deras hierarki (parent - child) är strukturerad. Ta hjälp av webbläsarens dev tools.

- Vad är huvudelementets (Direkt i `<body>`) "nearest child"?
  - Hur många children har den i sin tur?
- Vilka delar är siblings?
  - Har navigeringen och textinnehållet samma parent?
  - Ligger rubriken utanför ovanståendes parent element?

## 👨‍💻 Gör alla ändringar i `index.html`

```html
<!DOCTYPE html>
<html>
  <head> </head>
  <body>
    // alla element läggs här inom
  </body>
</html>
```

## 🎁 Bonusuppgifter

### Byt till semantisk HTML

Förbättra SEO och tillgänglighet med element som enkelt kan tolkas av skärmläsare.

- [dbwebb.se - Semantisk HTML](https://dbwebb.se/guide/design-med-html5-och-css3/semantisk-html)
- [Lista på relevanta element](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements#content_sectioning)
- [Explained in 4 minutes: Semantic HTML](https://www.youtube.com/watch?v=YPzFPoqwTmI)

### Lägg till språk för hela HTML-filen

I taggen som wrappar hela filen.

### Ändringar i `<head>`

- Ge webbsidan en titel
- Lägg till favicon
- Lägg till document encoding
