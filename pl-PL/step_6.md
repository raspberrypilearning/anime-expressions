## Kolory i czcionki

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

W tym kroku możesz wypróbować różne palety kolorów i czcionki.

</div>
<div>
<iframe src="https://editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-6" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

Teraz, gdy zacząłeś dodawać niestandardowe klasy do swojego kodu, być może zauważyłeś, że kolor został dodany do strony. W CSS możesz użyć **zmiennych**, aby stworzyć paletę kolorów dla swojej strony internetowej.

Zmienne CSS zaczynają się od dwóch myślników: "--primary".

Kolory są określane przy użyciu notacji szesnastkowej (heksadecymalnej) i zaczynają się od '#'. Istnieje wiele stron internetowych, na których możesz znaleźć kolory heksadecymalne do użycia.

\--- task ---

Przejdź do pliku „candy.css”. Ten plik ustawia zmienne kolorów dla palety kolorów cukierków.

W palecie kolorów cukierków zmienna "--primary" jest ustawiona na "#ebeaeb", bladoszary.

## --- code ---

language: CSS
filename: candy.css
line_numbers: true
line_number_start: 1
line_highlights: 4
-------------------------------------------------------

/\* Paleta kolorów i czcionki cukierków \*/

:root {
\--primary: #ebeaeb;
\--onprimary: #625d61;
\--secondary: #f5bdd5;
\--onsecondary: #1d3d58;
\--tertiary: #b5a9b2;
\--ontertiary: #422215;
\--page: #ffffff;
\--onpage: #000000;
\--detail: #e697b9;
\--detail2: #415a89;

\--- /code ---

**Wskazówka:** CSS używa innych znaczników komentarzy niż HTML. Komentarze wielowierszowe zaczynają się od "/_" i kończą na "_/". Przeglądarka ignoruje kod znajdujący się wewnątrz znaczników komentarzy.

"/\* paleta kolorów i czcionki cukierków \*/" to przykład komentarza CSS.

\--- /task ---

Możesz również użyć zmiennych dla czcionek. "--header-font" jest ustawiony na "3rem 'Fredoka One', cursive;"

"3rem" oznacza, że czcionka ta powinna być trzykrotnie większa od normalnego rozmiaru czcionki.

"Fredoka One", kursywny oznacza, że przeglądarka powinna używać czcionki "Fredoka One", jeśli może. Jeśli ta czcionka nie jest dostępna, przeglądarka powinna użyć **fallback font**, który jest „kursywny”.

[[[web-fonts]]]

\--- task ---

**Znajdź** zmienne, które ustawiają czcionki dla Twojej strony internetowej.

## --- code ---

language: CSS
filename: candy.css
line_numbers: true
line_number_start: 15
line_highlights: 15-18
-----------------------------------------------------------

\--body-font: 1rem 'Verdana', sans-serif;
\--header-font: 3rem 'Fredoka One', cursive;
\--title-font: 2rem 'Fredoka One', cursive;
\--quote-font: lighter 1.5rem 'Chewy', cursive;
}

\--- /code ---

\--- /task ---

Kolory "podstawowe" są zaprojektowane tak, aby były używane najbardziej w głównej treści strony, a następnie kolory "drugorzędne", a następnie "trzeciorzędne". Oznacza to, że możesz z łatwością projektować nowe palety kolorów i przełączać się między nimi.

Projekt startowy zawiera również żywy plik palety kolorów o nazwie "vivid.css".

\--- task ---

**Znajdź** plik „vivid.css”.

Zauważ, że zmienne kolor i czcionka mają takie same nazwy jak w pliku candy.css, ale kolory i czcionki używane w tej palecie kolorów są inne.

## --- code ---

language: CSS
filename: vivid.css
line_numbers: true
line_number_start: 1
------------------------------------------------------------------------------

/\* Żywa paleta kolorów i czcionki \*/

:root {
\--primary: #68bbe5;
\--onprimary: #000000;
\--secondary: #e2008a;
\--onsecondary: #000000;
\--tertiary: #fdf100;
\--ontertiary: #000000;
\--page: #ffffff;
\--onpage: #000000;
\--detail: #ffa71a;
\--detail2: #41063c;

\--body-font: 1rem Verdana, sans-serif;
\--header-font: lighter 3rem "Bangers", cursive;
\--title-font: lighter 2rem "Bangers", cursive;
\--quote-font: lighter 1.5rem 'Chewy', cursive;
}

\--- /code ---

\--- /task ---

\--- task ---

Przejdź do "index.html" i zmień kod łącza CSS na link do pliku "vivid.css":

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 21
line_highlights: 24
--------------------------------------------------------

```
<!-- dołącz plik stylu CSS -->


<link href="style.css" rel="stylesheet" type="text/css" /> <link href="vivid.css" rel="stylesheet" type="text/css" />
```

\--- /code ---

\--- /task ---

\--- task ---

**Test:** Kliknij przycisk **Run**.

Upewnij się, że Twoja strona internetowa używa teraz jaśniejszych kolorów i różnych czcionek, zgodnie z definicją w pliku "vivid.css".

<iframe src="https://editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-6" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>

\--- /task ---
