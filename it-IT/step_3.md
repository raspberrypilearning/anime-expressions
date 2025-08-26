## Aggiungi un'espressione facciale

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In questo passaggio, aggiungi il primo disegno e le istruzioni per la tua pagina web.
</div>
<div>
<iframe src="https://editor.raspberrypi.org/it-IT/embed/viewer/anime-expressions-step-3" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

Per prima cosa, crea una sezione per ogni espressione facciale nella pagina web.

--- task ---

Trova il commento `<!--- Il primo disegno e le istruzioni vanno qui --->`.

Aggiungi i tag `<section></section>` per il tuo primo contenuto di disegno e istruzioni.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 40-42
---
    <main>
      <section>
        <h2>Espressioni del viso</h2>
        <p>Dai un'occhiata a queste espressioni facciali e provale nei tuoi disegni.</p>
      </section>
       
      <!-- Il primo disegno e le istruzioni vanno qui -->     
      <section>
          
      </section> 

--- /code ---

--- /task ---

Il tuo progetto di partenza contiene immagini da usare in questo progetto. Per includere un immagine nella pagina web, devi conoscere il nome del file. Per prima cosa, aggiungi un'immagine chiamata `love.png`.

--- task ---

All'interno della tua nuova sezione, aggiungi un tag `<img>` per visualizzare un'immagine. L'**attributo** `src` fornisce il nome dell'immagine.

Il tag`<img>` non ha un tag di chiusura.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---
      <!-- Il primo disegno e le istruzioni vanno qui -->     
      <section>
        <img src="love.png">
      </section> 

--- /code ---

--- /task ---

--- task ---

**Test:** Clicca sul pulsante **Esegui**.

L'immagine `love.png` appare nella tua pagina web.

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Testo alternativo (Alt)**</span> è la descrizione di un'immagine ed è importante nel web design accessibile per descrivere le immagini a chi non può vederle. Il testo non appare nella pagina web ma viene letto ad alta voce dagli screen readers.
</p>

--- task ---

Aggiungi l'attributo `alt` per fornire un testo alternativo per le persone che non possono vedere l'immagine.

Puoi copiare la descrizione della tua immagine e incollala all'interno del tuo codice: `L'espressione facciale dell'amore.`

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---   
      <!-- Il primo disegno e le istruzioni vanno qui -->     
      <section>
        <img src="love.png" alt="L'espressione facciale dell'amore.">
      </section> 

--- /code ---

--- /task ---

--- task ---

Aggiungi un paragrafo di testo nei tag `<p></p>` per descrivere come disegnare l'espressione facciale anime dell'amore.

Puoi copiare il paragrafo e incollarlo nel tuo codice: `<p>Per fare in modo che il tuo personaggio anime sembri innamorato, sostituisci i suoi occhi con due cuori arrotondati. Puoi aggiungere altri tre cuori all'interno per un effetto divertente.</p>`

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 42
---   
      <!-- Il primo disegno e le istruzioni vanno qui -->     
      <section>
        <img src="love.png" alt="L'espressione facciale dell'amore.">
        <p>Per fare in modo che il tuo personaggio anime sembri innamorato, sostituisci i suoi occhi con due cuori arrotondati. Puoi aggiungere altri tre cuori all'interno per un effetto divertente.</p>
      </section> 

--- /code ---

--- /task ---

Il tag `<strong>` rende il testo importante **in grassetto**.

--- task ---

Aggiungi i tag `<strong>` attorno alla parola 'amore':

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 42
---   
      <!-- Il primo disegno e le istruzioni vanno qui -->     
      <section>
        <img src="love.png" alt="L'espressione facciale dell'amore.">
        <p>Per fare in modo che il tuo personaggio anime sembri <strong>innamorato</strong>, sostituisci i suoi occhi con due cuori arrotondati. Puoi aggiungere altri tre cuori all'interno per un effetto divertente.</p>
      </section> 

--- /code ---

--- /task ---

--- task ---

**Test:** Clicca sul pulsante **Esegui**.

Le istruzioni appaiono sotto la tua immagine e la parola **amore** è in grassetto.

<iframe src="https://editor.raspberrypi.org/it-IT/embed/viewer/anime-expressions-step-3" width="500" height="750" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
--- /task ---

