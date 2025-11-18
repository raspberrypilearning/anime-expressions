## Estilo con clases

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

Este paso te muestra cómo agregar clases para personalizar los estilos de tu página.

</div>
<div>
<iframe src="https://editor.raspberrypi.org/es-LA/embed/viewer/anime-expressions-step-5" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

Si quieres aplicar estilo a elementos específicos, puedes crear una **clase** en un archivo CSS. Luego puedes añadir un **atributo** `class=` a un elemento en tu código HTML para que el navegador sepa qué estilo se debe aplicar.

El estilo de clase sobreescribe cualquier estilo de elemento que ya ha sido aplicado. Tenga en cuenta que los cambios tienen lugar a medida que añade las clases a su código.

--- task ---

Tu archivo CSS tiene una clase CSS personalizada llamada `border-bottom`. Esta clase añade un borde de línea grueso y de color sólido a la parte inferior de cualquier elemento HTML que lo utilice.

Ve a tu archivo `index.html` y encuentra tu `header`.

Añade `class="border-bottom"` después de la palabra `header` en tu etiqueta `header`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 27
line_highlights: 29
---
  <body>
    <!-- El código del encabezado de la página va aquí -->
    <header class="border-bottom">
      <h1>Dibuja anime conmigo</h1>
    </header>

--- /code ---

--- /task ---

--- task ---

Añade la clase `border-top` a tu código `footer` para aplicar un borde grueso a la parte superior de tu pie de página.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 55
line_highlights: 56
---
    <!-- Pie de página web -->
    <footer class="border-top">

--- /code ---

--- /task ---

La clase `primary` establece un contraste de fondo y color de texto para la mayoría del contenido principal.

La clase `secondary` establece una combinación de colores adicional que se ve bien con los colores de la clase `primary`.

--- task ---

Añade la clase `secondary` a tu código `footer` para aplicar un fondo de color diferente a tu pie de página.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 55
line_highlights: 56
---
    <!-- Pie de página web -->
    <footer class="border-top secondary">

--- /code ---

--- /task ---

--- task ---

Añade `class="primary"` a `<main>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 34
---
    <!-- El contenido principal de la página web va entre las etiquetas principales -->
    <main class="primary">

--- /code ---

--- /task ---

--- task ---

Añade `secondary` a `<header>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 28
line_highlights: 29
---
    <!-- El código del encabezado de la página va aquí -->
    <header class="border-bottom secondary">

--- /code ---

--- /task ---

La clase `tertiary` establece una combinación de colores adicional que lucen bien con los colores de las clases `primary` y `secondary`.

--- task ---

Añade `class="tertiary"` al **primer** elemento `<section>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 35
---
    <!-- El contenido principal de la página web va entre las etiquetas principales -->
    <main class="primary">
      <section class="tertiary">
        <h2>Expresiones faciales</h2>
        <p class="xcenter">Echa un vistazo a estas expresiones faciales e intentalas en tus propios dibujos.</p>
      </section>

--- /code ---

La clase `xcenter` en tu archivo CSS alinea los elementos horizontalmente en la página.

--- /task ---

--- task ---

Añade `class="xcenter"` al `<p>` en la misma sección.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 37
---
    <!-- El contenido principal de la página web va entre las etiquetas principales -->
    <main class="primary">
      <section class="tertiary">
        <h2>Expresiones faciales</h2>
        <p class="xcenter">Echa un vistazo a estas expresiones faciales e intentalas en tus propios dibujos.</p>
      </section>

--- /code ---

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Las páginas web pueden ser vistas en muchos dispositivos diferentes y deben ser <span style="color: #0faeb0">**responsivas**</span> para cada dispositivo. Esto significa que si un usuario ve su página en un teléfono móvil, debería responder a una pantalla más pequeña y si la ven en un PC de escritorio, debería responder a una pantalla más grande. 
</p>

CSS puede cambiar el diseño en una página web, también se utiliza para cambiar colores, fuentes y bordes.

--- task ---

Encuentra el **second** `<section>`.

Añade `class="wrap"` a la etiqueta `<section>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 40
---
    <!-- El primer dibujo e instrucciones van aquí -->
    <section class="wrap">
      <img src="love.png" alt="La expresión facial del amor.">
      <p>Para que tu personaje parezca enamorado, reemplaza sus ojos con dos corazones redondeados. Puedes agregar otros tres corazones dentro para crear un efecto divertido.</p>
    </section>

--- /code ---

--- /task ---

También puedes añadir bordes de color en diferentes estilos a los elementos HTML. La clase `dashed-border` en el archivo de estilo crea un borde discontinuo.

--- task ---

Añade la clase `dashed-border` a la `<img>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---
    <!-- El primer dibujo e instrucciones van aquí -->
    <section class="wrap">
      <img class="dashed-border" src="love.png" alt="La expresión facial del amor.">
      <p>Para que tu personaje parezca enamorado, reemplaza sus ojos con dos corazones redondeados. Puedes agregar otros tres corazones dentro para crear un efecto divertido.</p>
    </section>

--- /code ---

--- /task ---

Puedes hacer que las esquinas de un elemento sean redondeadas con la clase `rounded`.

--- task ---

Añade la clase `rounded` a `<img>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---
    <!-- El primer dibujo e instrucciones van aquí -->
    <section class="wrap">
      <img class="dashed-border rounded" src="love.png" alt="La expresión facial del amor.">
      <p>Para que tu personaje parezca enamorado, reemplaza sus ojos con dos corazones redondeados. Puedes agregar otros tres corazones dentro para crear un efecto divertido.</p>
    </section>

--- /code ---

--- /task ---

--- task ---

**Prueba:** Haz clic en el botón **Ejecutar**.

Arrastra la barra entre el editor de texto y tu página web para hacer la página web más estrecha.

El texto debe moverse por debajo de la imagen. Esta es la disposición para los usuarios que ven la página web en un teléfono móvil.

Arrastre la barra después de probarla, para que pueda ver la imagen y el texto lado a lado.

![En el Editor, el espacio vertical entre los dos paneles se arrastra de izquierda a derecha para mostrar que la página web se ajusta a pantallas más pequeñas.](images/drag-window.gif)

--- /task ---
