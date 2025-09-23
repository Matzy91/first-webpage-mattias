# Bootcamp FMW2025 - ♿️ CSS + Grundläggande UX

Vi fortsätter med styling även denna vecka och introducerar grundläggande UX- och tillgänglighetsprinciper i och med att de många gånger går hand i hand. Syftet med denna uppgift är att göra er statiska webbsida så tillgänglig och responsiv som möjligt.

## 👩‍🔧 Förberedelser

1. Installera tillägget [W3C Web Validator](https://marketplace.visualstudio.com/items?itemName=CelianRiboulet.webvalidator). i VS Code
2. Tryck på "WC3 validation" helt nederst till vänster i VS Code-fönstret och undersök vilka delar av HTML-koden som blev understrukna. Håll musen över för att läsa om felet/varningen.
3. Lös alla fel och varningar.

## ☯️ Fokuspunkter

Utöver WC3-validering kan det finnas andra förbättringsområden på webbsidan. Undersök den med dessa fokuspunkter i åtanke

### Kontrast

Är all text enkel att urskilja? Står textfärgen i tillräckligt stark kontrast till bakgrundsfärgen?

### Skärmläsare

Kan en skärmläsare enkelt tyda sidan? Finns det beskrivningar på alla element som inte innehåller text? Är HTML-elementen semantiska?

### Intuitivitet

Är det tydligt vilka element som är interaktiva? Är det lätt för en användare som aldrig sett sidan för hur man navigerar till de olika sidorna? Vilken CTA-knappen (Call to action) är?

### Responsivitet

Hur ser sidan ut på olika skärmstorlekar? Blir layouten rörigt på mobil? Använd DevTools för jämföra.

## 📱 Mobilanpassa sidan

Skapa relevanta `@media` queries så att sidan ser bra ut och är enkel att navigera även på en mobilskärm. Glöm inte att skifta mellan liten och stor skärm för att säkerställa att ändringarna inte har några oönskade biverkningar.

Det är inte alltid som media queries behövs för god responsivitet. Du kan också testa att använda dynmaiska properties och värden som `clamp()`, `%`, `vw` etc.

## 🎁 Bonusuppgifter

### CSS Variables

Skapa variabler för alla värden som används upprepade gånger.

## A11y rules

Typiska regler som måste följas för optimal tillgänglighet på webben inkluderar:

- Document type: [Doctype syntax](https://w3c.github.io/html/syntax.html#the-doctype)

- Page title: [Web pages have titles that describe topic or purpose](https://www.w3.org/TR/2008/REC-WCAG20-20081211/#navigation-mechanisms-title)

- Document Language: [The default human language of each Web page can be programmatically determined](https://www.w3.org/TR/2008/REC-WCAG20-20081211/#meaning-doc-lang-id)

- Document encoding: [Declaring character encodings in HTML ](https://www.w3.org/International/questions/qa-html-encoding-declarations)

- Document scalable: [Resize text](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-scale.html)

- Heading: [Headings and sections](https://www.w3.org/TR/2014/REC-html5-20141028/sections.html#headings-and-sections)

- Images: [Every image must have an alt attribute](https://webaim.org/techniques/alttext/)

- Links: [Providing context for the links](https://www.w3.org/TR/2013/NOTE-WCAG20-TECHS-20130905/G53)

- Buttons: [Providing descriptive text for buttons](https://www.w3.org/TR/WCAG20-TECHS/FLASH27.html)

- Forms: [Providing descriptive label for forms](https://www.w3.org/TR/2014/NOTE-WCAG20-TECHS-20140408/H44)

- Iframes: [Providing descriptive title for iframes](https://www.w3.org/TR/2014/NOTE-WCAG20-TECHS-20140408/H64)

- Audios: [Providing an alternative for time-based media for audio-only content](https://www.w3.org/TR/WCAG20-TECHS/G158.html)

- Videos: [Providing an alternative for time-based media for video-only content](https://www.w3.org/TR/WCAG20-TECHS/G159.html)

- Positive tabindex value: [Focus order](https://www.w3.org/TR/2008/REC-WCAG20-20081211/#navigation-mechanisms-focus-order)
- Unique IDs: [the id attribute value must be unique](https://www.w3.org/TR/html5/dom.html#ref-for-concept-id⑦)
