\--- question ---

---

## legend: Vraag 2 van 3

CSS-classes kunnen op HTML-code worden toegepast om te beslissen hoe de inhoud in de webbrowser moet verschijnen.

Hieronder vind je wat CSS-code voor het opmaken van een subkop. Welke regel code zou je veranderen om de ondertitel aan de rechterkant weer te geven?

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

Kijk nog een keer. De eerste regel zegt dat de **selector** waarop de regel van toepassing is, de 'h2' tag is.

\--- /feedback ---

- ( ) 2

  \--- feedback ---

Niet helemaal. De tweede regel zegt dat het lettertype voor elementen met de `h2`-tag wordt geleverd door de `--title-font` **variabele**.

\--- /feedback ---

- (x) 3

  \--- feedback ---

  Juist! Met de derde regel kun je de uitlijning van de tekst wijzigen. Door 'left' in 'right' te veranderen, wordt de tekst aan de rechterkant uitgelijnd.

  \--- /feedback ---

- ( ) 4

  \--- feedback ---

  Probeer het nog eens. Met de vierde regel kun je de ruimte rond de subkop aanpassen.

  \--- /feedback ---

\--- /choices ---

\--- /question ---
