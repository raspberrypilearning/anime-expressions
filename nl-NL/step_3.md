## Voeg een gezichtsuitdrukking toe

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Voeg in deze stap de eerste tekening en instructie toe aan jouw webpagina.
</div>
<div>
<iframe src="https://editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-3" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

Maak eerst een sectie voor elke gezichtsuitdrukking op de webpagina.

\--- task ---

Zoek de opmerking `<!-- De eerste tekening en instructies komen hier -->`.

Voeg de `<section></section>` tags toe voor je eerste tekening en instructie-inhoud.

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 40-42
-----------------------------------------------------------

```
<main>
  <section>
    <h2>Facial expressions</h2>
    <p>Take a look at these facial expressions and try them in your own drawings.</p>
  </section>
   
  <!-- The first drawing and instructions go here -->     
  <section>
      
  </section> 
```

\--- /code ---

\--- /task ---

Het startproject bevat afbeeldingen om te gebruiken in dit project. Om een afbeelding op een webpagina toe te voegen, moet je de bestandsnaam weten. Voeg eerst een afbeelding toe met de naam `love.png`.

\--- task ---

Voeg binnen je nieuwe sectie een `<img>` tag toe om een afbeelding weer te geven. Het `src` **attribuut** geeft de naam van de afbeelding.

De `<img>` tag heeft geen eindtag.

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
--------------------------------------------------------

```
  <!-- The first drawing and instructions go here -->     
  <section>
    <img src="love.png">
  </section> 
```

\--- /code ---

\--- /task ---

\--- task ---

**Test:** Klik op de **Run** knop.

De `love.png` afbeelding verschijnt op je webpagina.

\--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Alternatieve (Alt) tekst**</span> is een beschrijving van een afbeelding en is belangrijk in toegankelijk webdesign om afbeeldingen te beschrijven voor mensen die ze niet kunnen zien. De tekst verschijnt niet op de webpagina, maar wordt hardop door schermlezers gelezen.
</p>

\--- task ---

Voeg het `alt` attribuut toe om alternatieve tekst te bieden voor mensen die de afbeelding niet kunnen bekijken.

Je kunt de beschrijving van je afbeelding kopiëren en in je code plakken: `De liefdes gezichtsuitdrukking.`

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
--------------------------------------------------------

```
  <!-- The first drawing and instructions go here -->     
  <section>
    <img src="love.png" alt="The love facial expression.">
  </section> 
```

\--- /code ---

\--- /task ---

\--- task ---

Voeg een alinea met tekst toe in de tags '<p></p>' om te beschrijven hoe je de gezichtsuitdrukking van de liefdesanime tekent.

Je kunt de paragraaf kopiëren en in je code plakken:
`<p>Om je anime-personage er verliefd uit te laten zien, vervang je de ogen door twee ronde harten. Je kunt nog drie harten toevoegen voor een leuk effect.</p>`

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 42
--------------------------------------------------------

```
  <!-- The first drawing and instructions go here -->     
  <section>
    <img src="love.png" alt="The love facial expression.">
    <p>To make your anime character look like they are in love, replace the eyes with two rounded hearts. You can add three more hearts inside for a fun effect.</p>
  </section> 
```

\--- /code ---

\--- /task ---

De tag `<strong>` maakt belangrijke tekst **vetgedrukt**.

\--- task ---

Voeg '<strong>' tags toe rond het woord 'verliefd':

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 42
--------------------------------------------------------

```
  <!-- The first drawing and instructions go here -->     
  <section>
    <img src="love.png" alt="The love facial expression.">
    <p>To make your anime character look like they are in <strong>love</strong>, replace the eyes with two rounded hearts. You can add three more hearts inside for a fun effect.</p>
  </section> 
```

\--- /code ---

\--- /task ---

\--- task ---

**Test:** Klik op de **Run** knop.

De instructies verschijnen onder je afbeelding en het woord **verliefd** is vetgedrukt.

<iframe src="https://editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-3" width="500" height="750" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
--- /task ---

