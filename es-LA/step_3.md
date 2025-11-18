## Agrega una expresión facial

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
En este paso, añade el primer dibujo e instrucción a tu página web.
</div>
<div>
<iframe src="https://editor.raspberrypi.org/es-LA/embed/viewer/anime-expressions-step-3" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

Primero, crea una sección para cada expresión facial en la página web.

--- task ---

Encuentra el comentario `<!-- El primer dibujo e instrucciones van aquí -->`.

Añade en las etiquetas `<section></section>` para tu primer dibujo e instrucción de contenido.

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
        <h2>Expresiones faciales</h2>
        <p>Echa un vistazo a estas expresiones faciales e intentalas en tus propios dibujos.</p>
      </section>
       
      <!-- El primer dibujo e instrucciones van aquí -->     
      <section>
          
      </section> 

--- /code ---

--- /task ---

Tu proyecto de iniciación contiene imágenes para usar en este proyecto. Para incluir una imagen en una página web, es necesario conocer el nombre del archivo. Primero, añade una imagen llamada `love.png`.

--- task ---

Dentro de tu nueva sección, añade una etiqueta `<img>` para mostrar una imagen. El **atributo** `src` da el nombre de la imagen.

La etiqueta `<img>` no tiene una etiqueta final.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---
      <!-- El primer dibujo e instrucciones van aquí -->     
      <section>
        <img src="love.png">
      </section> 

--- /code ---

--- /task ---

--- task ---

**Prueba:** Haz clic en el botón **Ejecutar**.

La imagen `love.png` aparece en tu página web.

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Texto alternativo (Alt)**</span> es una descripción de una imagen y es importante en el diseño web accesible para describir imágenes a personas que no pueden verlas. El texto no aparece en la página web pero es leído en voz alta por los lectores de pantalla.
</p>

--- task ---

Añade el atributo `alt` para proporcionar texto alternativo para las personas que no pueden ver la imagen.

Puedes copiar la descripción de tu imagen y pegarla en tu código: `La expresión facial del amor.`

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---   
      <!-- El primer dibujo e instrucciones van aquí -->     
      <section>
        <img src="love.png" alt="La expresión facial del amor.">
      </section> 

--- /code ---

--- /task ---

--- task ---

Añade un párrafo de texto en las etiquetas `<p></p>` para describir cómo dibujar la expresión facial del anime de amor.

Puedes copiar el párrafo y pegarlo en tu código:
`<p>Para que tu personaje anime se vea enamorado, reemplaza los ojos por dos corazones redondeados. Puedes añadir tres corazones más dentro para un efecto divertido.</p>`

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 42
---   
      <!-- El primer dibujo e instrucciones van aquí -->     
      <section>
        <img src="love.png" alt="La expresión facial del amor.">
        <p>Para que tu personaje parezca enamorado, reemplaza sus ojos con dos corazones redondeados. Puedes agregar otros tres corazones dentro para crear un efecto divertido.</p>
      </section> 

--- /code ---

--- /task ---

La etiqueta `<strong>` hace que el texto importante esté **negrita**.

--- task ---

Añade etiquetas `<strong>` alrededor de la palabra 'amor':

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 42
---   
      <!-- El primer dibujo e instrucciones van aquí -->     
      <section>
        <img src="love.png" alt="La expresión facial del amor.">
        <p>ara que tu personaje parezca <strong>enamorado</strong>, reemplaza sus ojos con dos corazones redondeados. Puedes agregar otros tres corazones dentro para crear un efecto divertido.</p>
      </section> 

--- /code ---

--- /task ---

--- task ---

**Prueba:** Haz clic en el botón **Ejecutar**.

Las instrucciones aparecen debajo de tu imagen y la palabra **amor** está en negrita.

<iframe src="https://editor.raspberrypi.org/es-LA/embed/viewer/anime-expressions-step-3" width="500" height="750" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
--- /task ---

