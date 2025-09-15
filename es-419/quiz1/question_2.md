\--- question ---

---

## leyenda: Pregunta 2 de 3

Las clases CSS se pueden aplicar al código HTML para decidir cómo debe aparecer el contenido en el navegador web.

Debajo hay un código CSS para diseñar un subtítulo. ¿Qué línea de código cambiaría para hacer que el subtítulo se muestre en el lado derecho?

## --- code ---

language: css
filename: style.css
line_numbers: true
line_number_start: 1
line_highlights:
-----------------------------------------------------

h2 {
font: var(--title-font);
text-align: left;
padding: 1.5rem;
}

\--- /code ---

\--- choices ---

- ( ) 1

  \--- feedback ---

Echa otro vistazo. La primera línea dice que el **selector** al que se aplica la regla es la etiqueta `h2`.

\--- /feedback ---

- ( ) 2

  \--- feedback ---

No exactamente. La segunda línea dice que la fuente para elementos con la etiqueta `h2` es proporcionada por la **variable `--title-font`**.

\--- /feedback ---

- (x) 3

  \--- feedback ---

  ¡Correcto! La tercera línea le permite cambiar la alineación del texto. Cambiando `izquierda` a `derecha`, el texto se alinearía a la derecha.

  \--- /feedback ---

- ( ) 4

  \--- feedback ---

  Intenta de nuevo. La cuarta línea le permite ajustar el espacio alrededor del subtítulo.

  \--- /feedback ---

\--- /choices ---

\--- /question ---
