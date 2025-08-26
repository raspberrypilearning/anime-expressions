## Personalizza con le classi

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

Questo passaggio ti mostra come aggiungere classi per personalizzare gli stili nella tua pagina.

</div>
<div>
<iframe src="https://editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-5" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

Se vuoi applicare uno stile a elementi specifici, puoi creare una **classe** in un file CSS. Puoi poi aggiungere un'**attributo** `class=` ad un elemento nel tuo codice HTML per indicare al browser quale stile deve essere applicato.

Lo stile della classe sovrascrive qualsiasi stile dell'elemento che è già stato applicato. Puoi notare che le modifiche avvengono quando aggiungi le classi al tuo codice.

\--- task ---

Il tuo file CSS ha una classe CSS personalizzata chiamata `border-bottom`. Questa classe aggiunge un bordo spesso e colorato alla parte inferiore di qualsiasi elemento HTML che la utilizza.

Vai al tuo file `index.html` e trova il tuo `header`.

Aggiungi `class="border-bottom"` dopo la parola `header` nel tuo tag `header`.

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 27
line_highlights: 29
--------------------------------------------------------

  <body>
    <!-- The page header code goes here -->
    <header class="border-bottom">
      <h1>Draw anime with me</h1>
    </header>

\--- /code ---

\--- /task ---

\--- task ---

Aggiungi la classe `border-top` al tuo codice `footer` per applicare un bordo spesso alla parte superiore del piè di pagina.

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 55
line_highlights: 56
--------------------------------------------------------

```
<!-- Webpage footer -->
<footer class="border-top">
```

\--- /code ---

\--- /task ---

La classe `primary` imposta uno sfondo e un colore del testo contrastanti per la maggior parte del contenuto principale.

La classe `secondary` imposta una combinazione di colori aggiuntiva che si abbina bene ai colori della classe `primary`.

\--- task ---

Aggiungi la classe `secondary` al tuo codice `footer` per applicare uno sfondo di colore diverso al tuo piè di pagina.

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 55
line_highlights: 56
--------------------------------------------------------

```
<!-- Webpage footer -->
<footer class="border-top secondary">
```

\--- /code ---

\--- /task ---

\--- task ---

Aggiungi `class="primary"` a `<main>`.

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 34
--------------------------------------------------------

```
<!-- The main content for the webpage goes between the main tags -->
<main class="primary">
```

\--- /code ---

\--- /task ---

\--- task ---

Aggiungi `secondary` a `<header>`.

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 28
line_highlights: 29
--------------------------------------------------------

```
<!-- The page header code goes here -->
<header class="border-bottom secondary">
```

\--- /code ---

\--- /task ---

La classe `tertiary`imposta una combinazione di colori aggiuntiva che si abbina bene ai colori delle classi `primary` e `secondary`.

\--- task ---

Aggiungi `class="tertiary"`al **primo** elemento\*\* `<section>`.

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 35
--------------------------------------------------------

```
<!-- The main content for the webpage goes between the main tags -->
<main class="primary">
  <section class="tertiary">
    <h2>Facial expressions</h2>
    <p class="xcenter">Take a look at these facial expressions and try them in your own drawings.</p>
  </section>
```

\--- /code ---

La classe `xcenter` nel tuo file CSS allinea gli elementi orizzontalmente attraverso la pagina.

\--- /task ---

\--- task ---

Aggiungi `class="xcenter"` a `<p>` nella stessa sezione.

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 37
--------------------------------------------------------

```
<!-- The main content for the webpage goes between the main tags -->
<main class="primary">
  <section class="tertiary">
    <h2>Facial expressions</h2>
    <p class="xcenter">Take a look at these facial expressions and try them in your own drawings.</p>
  </section>
```

\--- /code ---

\--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Le pagine web possono essere visualizzate su diversi dispositivi e dovrebbero essere <span style="color: #0faeb0">**reattive**</span> per ogni dispositivo. Questo significa che se gli utenti visualizzano la pagina su un telefono cellulare, dovrebbe rispondere a uno schermo più piccolo e se lo visualizzano sul up PC desktop, dovrebbe rispondere a uno schermo più grande. 
</p>

Il CSS può cambiare il layout di una pagina web, oltre a essere usato per cambiare colori, font e bordi.

\--- task ---

Trova il **secondo** `<section>`.

Aggiungi `class="wrap"` al tag `<section>`.

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 40
--------------------------------------------------------

```
<!-- The first drawing and instructions go here -->
<section class="wrap">
  <img src="love.png" alt="The love facial expression.">
  <p>To make your anime character look like they are in love, replace the eyes with two rounded hearts. You can add three more hearts inside for a fun effect.</p>
</section>
```

\--- /code ---

\--- /task ---

Puoi anche aggiungere bordi colorati in diversi stili agli elementi HTML. La classe `dashed-border` nel file di stile crea un bordo tratteggiato.

\--- task ---

Aggiungi la classe `dashed-border` a `<img>`.

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
--------------------------------------------------------

```
<!-- The first drawing and instructions go here -->
<section class="wrap">
  <img class="dashed-border" src="love.png" alt="The love facial expression.">
  <p>To make your anime character look like they are in love, replace the eyes with two rounded hearts. You can add three more hearts inside for a fun effect.</p>
</section>
```

\--- /code ---

\--- /task ---

Puoi arrotondare gli angoli di un elemento con la classe `rounded`.

\--- task ---

Aggiungi la classe `rounded` a `<img>`.

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
--------------------------------------------------------

```
<!-- The first drawing and instructions go here -->
<section class="wrap">
  <img class="dashed-border rounded" src="love.png" alt="The love facial expression.">
  <p>To make your anime character look like they are in love, replace the eyes with two rounded hearts. You can add three more hearts inside for a fun effect.</p>
</section>
```

\--- /code ---

\--- /task ---

\--- task ---

**Test:** Clicca sul pulsante **Esegui**.

Trascina la barra tra l'editor di testo e la tua pagina web per restringere la pagina web.

Il testo dovrebbe spostarsi sotto l'immagine. Questo è il layout per gli utenti che visualizzano la pagina web su un telefono cellulare.

Trascina indietro la barra dopo averla testata, in modo da poter vedere l'immagine e il testo affiancati.

![Nell'Editor, lo spazio verticale tra i due riquadri viene trascinato da sinistra a destra per mostrare che la pagina web si adatta per schermi più piccoli.](images/drag-window.gif)

\--- /task ---
