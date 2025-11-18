## Agrega una expresión facial

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
En este paso, añade el primer dibujo e instrucción a tu página web.
</div>
<div>
<iframe src="https://editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-3" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

Primero, crea una sección para cada expresión facial en la página web.

\--- task ---

Encuentra el comentario `<!-- El primer dibujo e instrucciones van aquí -->`.

Añade en las etiquetas `<section></section>` para tu primer dibujo e instrucción de contenido.

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

Tu proyecto de iniciación contiene imágenes para usar en este proyecto. Para incluir una imagen en una página web, es necesario conocer el nombre del archivo. Primero, añade una imagen llamada `love.png`.

\--- task ---

Dentro de tu nueva sección, añade una etiqueta `<img>` para mostrar una imagen. El **atributo** `src` da el nombre de la imagen.

La etiqueta `<img>` no tiene una etiqueta final.

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

**Prueba:** Haz clic en el botón **Ejecutar**.

La imagen `love.png` aparece en tu página web.

\--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Texto alternativo (Alt)**</span> es una descripción de una imagen y es importante en el diseño web accesible para describir imágenes a personas que no pueden verlas. El texto no aparece en la página web pero es leído en voz alta por los lectores de pantalla.
</p>

\--- task ---

Añade el atributo `alt` para proporcionar texto alternativo para las personas que no pueden ver la imagen.

Puedes copiar la descripción de tu imagen y pegarla en tu código: `La expresión facial del amor.`

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

Añade un párrafo de texto en las etiquetas `<p></p>` para describir cómo dibujar la expresión facial del anime de amor.

Puedes copiar el párrafo y pegarlo en tu código:
`<p>Para que tu personaje anime se vea enamorado, reemplaza los ojos por dos corazones redondeados. Puedes añadir tres corazones más dentro para un efecto divertido.</p>`

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

La etiqueta `<strong>` hace que el texto importante esté **negrita**.

\--- task ---

Añade etiquetas `<strong>` alrededor de la palabra 'amor':

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

**Prueba:** Haz clic en el botón **Ejecutar**.

Las instrucciones aparecen debajo de tu imagen y la palabra **amor** está en negrita.

<iframe src="https://editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-3" width="500" height="750" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
--- /task ---

