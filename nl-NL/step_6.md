## Kleuren en lettertypen

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

In deze stap kun je verschillende kleurenpalet en lettertype keuzes proberen.

</div>
<div>
<iframe src="https://editor.raspberrypi.org/nl-NL/embed/viewer/anime-expressions-step-6" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

Nu je bent begonnen om aangepaste classes aan je code toe te voegen, is het je misschien al opgevallen dat er kleur aan de pagina is toegevoegd. In CSS kun je **variabelen** gebruiken om een kleurenpalet te maken voor je webpagina.

CSS variabelen beginnen met twee streepjes: `--primary`.

Kleuren worden gespecificeerd met behulp van hexadecimale notatie (hex) en beginnen met '#'. Er zijn veel websites waar je hexadecimale kleuren kunt vinden die je kunt gebruiken.

--- task ---

Ga naar je `candy.css` bestand. Dit bestand stelt de kleurvariabelen in voor het snoepjeskleur palet.

In het snoepjeskleurenpalet is de `--primary` variabele ingesteld op `#ebeaeb`, lichtgrijs.

--- code ---
---
language: CSS
filename: candy.css
line_numbers: true
line_number_start: 1
line_highlights: 4
---
/* Snoepjes kleurenpalet en lettertypen */

:root {
  --primary: #ebeaeb;
  --onprimary: #625d61;
  --secondary: #f5bdd5;
  --onsecondary: #1d3d58;
  --tertiary: #b5a9b2;
  --ontertiary: #422215;
  --page: #ffffff;
  --onpage: #000000;
  --detail: #e697b9;
  --detail2: #415a89;

--- /code ---

**Tip:** CSS gebruikt andere markeringen voor opmerkingen dan HTML. Een opmerking van meerdere regels begint met `/*` en eindigt met `*/`. De browser negeert code die zich binnen de commentaarmarkeringen bevindt.

`/* Snoepjeskleur palet en lettertypen */` is een voorbeeld van een CSS opmerking.

--- /task ---

Je kunt ook variabelen voor lettertypen gebruiken. De `--header-font` is ingesteld op `3rem 'Fredoka One', cursive;`

`3rem` betekent dat dit lettertype drie keer de normale lettergrootte moet zijn.

`'Fredoka One', cursive' betekent dat de browser indien mogelijk het lettertype 'Fredoka One' moet gebruiken. Als dit lettertype niet beschikbaar is, moet de browser het **fallback font** gebruiken, wat`cursive\` is.

[[[web-fonts]]]

--- task ---

**Zoek** de variabelen die de lettertypen voor je webpagina instellen.

--- code ---
---
language: CSS
filename: candy.css
line_numbers: true
line_number_start: 15
line_highlights: 15-18
---

  --body-font: 1rem 'Verdana', sans-serif;
  --header-font: 3rem 'Fredoka One', cursive;
  --title-font: 2rem 'Fredoka One', cursive;
  --quote-font: lighter 1.5rem 'Chewy', cursive;
}

--- /code ---

--- /task ---

De `primary` kleuren zijn ontworpen om te gebruiken in het grootste gedeelte van de hoofdinhoud van de pagina, gevolgd door `secondary` en vervolgens `tertiary` kleuren. Dit betekent dat je gemakkelijk nieuwe kleurenpaletten kunt ontwerpen en tussen deze paletten kunt wisselen.

Het startproject bevat ook een levendig kleurenpalet bestand genaamd `vivid.css`.

--- task ---

**Zoek** het `vivid.css` bestand.

Je zult zien dat de kleur- en lettertype-variabelen dezelfde namen hebben als in het 'candy.css\` bestand, maar de gebruikte kleuren en lettertypen zijn verschillend in dit kleurenpalet.

--- code ---
---
language: CSS
filename: vivid.css
line_numbers: true
line_number_start: 1
---

/* Levendig kleurenpalet en lettertypen */

:root {
  --primary: #68bbe5;
  --onprimary: #000000;
  --secondary: #e2008a;
  --onsecondary: #000000;
  --tertiary: #fdf100;
  --ontertiary: #000000;
  --page: #ffffff;
  --onpage: #000000;
  --detail: #ffa71a;
  --detail2: #41063c;

  --body-font: 1rem Verdana, sans-serif;
  --header-font: lighter 3rem "Bangers", cursive;
  --title-font: lighter 2rem "Bangers", cursive;
  --quote-font: lighter 1.5rem 'Chewy', cursive;
} 

--- /code ---

--- /task ---

--- task ---

Ga naar `index.html` en verander de CSS link code om te linken naar het `vivid.css` bestand:

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 21
line_highlights: 24
---   
    <!-- Voeg de CSS style file toe -->

    <link href="style.css" rel="stylesheet" type="text/css" />
    <link href="vivid.css" rel="stylesheet" type="text/css" />

--- /code ---

--- /task ---

--- task ---

**Test:** Klik op de **Run** knop.

Check dat jouw webpagina nu de helderdere kleuren en verschillende lettertypen gebruikt, zoals gedefinieerd in het `vivid.css` bestand.

<iframe src="https://editor.raspberrypi.org/nl-NL/embed/viewer/anime-expressions-step-6" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>

--- /task ---
