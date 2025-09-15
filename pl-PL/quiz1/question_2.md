\--- question ---

---

## Legenda: Pytanie 2 z 3

Klasy CSS mogą być stosowane do kodu HTML, aby zdecydować, jak zawartość powinna wyglądać w przeglądarce internetowej.

Poniżej znajduje się kod CSS do stylizacji podpozycji. Który wiersz kodu zmieniłbyś, aby podtytuł był wyświetlany po prawej stronie?

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

Spójrz jeszcze raz. Pierwsza linia mówi, że **selektor**, do którego odnosi się reguła, to znacznik „h2”.

\--- /feedback ---

- ( ) 2

  \--- feedback ---

Nie do końca. Druga linia mówi, że czcionka dla elementów ze znacznikiem "h2" jest dostarczana przez "--title-font" **zmienną**.

\--- /feedback ---

- (x) 3

  \--- feedback ---

  Dobrze! Trzecia linia pozwala zmienić wyrównanie tekstu. Zmieniając "lewy" na "prawy", tekst będzie wyrównany po prawej stronie.

  \--- /feedback ---

- ( ) 4

  \--- feedback ---

  Spróbuj ponownie. Czwarta linia pozwala dostosować przestrzeń wokół podpozycji.

  \--- /feedback ---

\--- /choices ---

\--- /question ---
