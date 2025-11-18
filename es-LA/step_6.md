## Colores y fuentes

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

En este paso, puedes probar diferentes paletas de colores y opciones de fuentes.

</div>
<div>
<iframe src="https://editor.raspberrypi.org/es-LA/embed/viewer/anime-expressions-step-6" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

Ahora que ha comenzado a añadir clases personalizadas a su código, puede que haya notado que el color se ha añadido a la página. En CSS, puedes usar **variables** para crear una paleta de colores para tu página web.

Las variables CSS comienzan con dos guiones: `--primary`.

Los colores se especifican usando notación hexadecimal (hex) y empiezan con '#'. Hay muchos sitios web donde puedes encontrar colores hexadecimales para usar.

--- task ---

Ve a tu archivo `candy.css`. Este archivo establece las variables de para la paleta de colores candy.

En la paleta de colores candy, la variable `--primary` se establece en `#ebeaeb`, un gris pálido.

--- code ---
---
language: CSS
filename: candy.css
line_numbers: true
line_number_start: 1
line_highlights: 4
---
/* Paleta y fuentes de colores dulces */

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

**Tip:** CSS utiliza diferentes marcadores de comentarios a HTML. Los comentarios multiíneas comienzan con `/*` y terminan con `*/`. El navegador ignora el código que está dentro de los marcadores de comentarios.

`/* Paleta de colores candy y fuentes */` es un ejemplo de un comentario CSS.

--- /task ---

También puede utilizar variables para las fuentes. El `--header-font` se establece en `3rem 'Fredoka One', cursive;`

`3rem` significa que esta fuente debe ser tres veces el tamaño normal de la fuente.

`'Fredoka One', cursive` significa que el navegador debería usar la fuente 'Fredoka One' si es posible. Si esta fuente no está disponible, el navegador debería usar la **fallback font**, que es `cursive`.

[[[web-fonts]]]

--- task ---

**Encuentra** las variables que configuran las fuentes para tu página web.

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

Los colores `primary` están diseñados para ser utilizados más en el contenido principal de la página, seguido por los colores `secondary` y luego `tertiary`. Esto significa que puedes diseñar fácilmente nuevas paletas de colores y cambiar entre ellas.

El proyecto de iniciación también incluye un archivo de paleta de colores vívidos llamado `vivid.css`.

--- task ---

**Busca** el archivo `vivid.css`.

Tenga en cuenta que las variables de color y fuente tienen los mismos nombres que en el archivo `candy.css`, pero los colores y las fuentes utilizados son diferentes en esta paleta de colores.

--- code ---
---
language: CSS
filename: vivid.css
line_numbers: true
line_number_start: 1
---

/* Fuentes y paleta de colores vivos */

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

Ve a `index.html` y cambia el código de enlace CSS para enlazar al archivo `vivid.css`:

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 21
line_highlights: 24
---   
    <!-- Incluir archivo de estilo CSS -->

    <link href="style.css" rel="stylesheet" type="text/css" />
    <link href="vivid.css" rel="stylesheet" type="text/css" />

--- /code ---

--- /task ---

--- task ---

**Prueba:** Haz clic en el botón **Ejecutar**.

Asegúrese de que su página web utiliza ahora los colores más brillantes y las diferentes fuentes, como se define en el archivo `vivid.css`.

<iframe src="https://editor.raspberrypi.org/es-LA/embed/viewer/anime-expressions-step-6" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>

--- /task ---
