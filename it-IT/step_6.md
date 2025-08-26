## Colori e font

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

In questo passaggio, puoi provare diverse palette di colori e scelte di font.

</div>
<div>
<iframe src="https://editor.raspberrypi.org/it-IT/embed/viewer/anime-expressions-step-6" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

Ora che hai iniziato ad aggiungere classi personalizzate al tuo codice, potresti aver notato che alla pagina è stato aggiunto il colore. In CSS, puoi usare **variabili** per creare una palette di colori per la tua pagina web.

Le variabili CSS iniziano con due trattini: `--primary`.

I colori vengono specificati usando la notazione esadecimale (hex) e iniziano con '#'. Ci sono molti siti web dove è possibile trovare colori hex da utilizzare.

--- task ---

Vai al file `candy.css`. Questo file imposta le variabili colore per la palette di colori caramella.

Nella palette di colori caramella, la variabile `--primary` è impostata su `#ebeaeb`, un grigio pallido.

--- code ---
---
language: CSS
filename: candy.css
line_numbers: true
line_number_start: 1
line_highlights: 4
---
/* Palette di colori e font caramella */

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

**Suggerimento:** CSS utilizza marcatori di commento diversi da quelli HTML. I commenti multilinea iniziano con `/*` e finiscono con `*/`. Il browser ignora il codice che è all'interno dei marcatori di commento.

`/* Palette di colori e font caramella */` è un esempio di commento CSS.

--- /task ---

Puoi utilizzare variabili anche per i font. Il `--header-font` è impostato su `3rem 'Fredoka One', cursive;`

`3rem` significa che questo font dovrebbe essere tre volte più grande della dimensione normale del font.

`'Fredoka One', cursive` significa che il browser dovrebbe usare il font 'Fredoka One' se possibile. Se questo font non è disponibile, il browser dovrebbe usare il **font di riserva**, ovvero `cursive`.

[[[web-fonts]]]

--- task ---

**Trova** le variabili che impostano i font per la tua pagina web.

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

I colori `primary` sono progettati per essere utilizzati maggiormente nel contenuto principale della pagina, seguiti dai colori `secondary` e infine dai colori `tertiary`. Ciò significa che puoi facilmente progettare nuove palette di colori e passare da una all'altra.

Il progetto di partenza include anche un file di palette di colori vividi chiamato `vivid.css`.

--- task ---

**Trova** il file `vivid.css`.

Puoi notare che le variabili di colore e di font hanno gli stessi nomi del file `candy.css`, ma i colori e i font usati sono diversi in questa palette di colori.

--- code ---
---
language: CSS
filename: vivid.css
line_numbers: true
line_number_start: 1
---

\*Palette di colori e font vivaci */

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

Vai su `index.html` e cambia il codice link CSS per collegarlo al file `vivid.css`:

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 21
line_highlights: 24
---   
    <!-- Includi il file di stile CSS -->

    <link href="style.css" rel="stylesheet" type="text/css" />
    <link href="vivid.css" rel="stylesheet" type="text/css" />

--- /code ---

--- /task ---

--- task ---

**Test:** Clicca sul pulsante **Esegui**.

Assicurati che la tua pagina web ora utilizzi i colori più brillanti e i font diversi, come definito nel file `vivid.css`.

<iframe src="https://editor.raspberrypi.org/it-IT/embed/viewer/anime-expressions-step-6" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>

--- /task ---
