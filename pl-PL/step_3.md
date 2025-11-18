## Dodaj wyraz twarzy

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
W tym kroku dodaj pierwszy rysunek i instrukcję do swojej strony internetowej.
</div>
<div>
<iframe src="https://editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-3" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

Najpierw utwórz sekcję dla każdego wyrazu twarzy na stronie internetowej.

\--- task ---

Znajdź komentarz "<!-- pierwszy rysunek i instrukcje przejdź tutaj -->".

Dodaj znaczniki „<section> </section>” dla swojego pierwszego rysunku i treści instrukcji.

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

Twój projekt startowy zawiera obrazy do wykorzystania w tym projekcie. Aby dołączyć obraz na stronie internetowej, musisz znać nazwę pliku. Najpierw dodaj obraz o nazwie "love.png".

\--- task ---

Wewnątrz nowej sekcji dodaj znacznik „<img>”, aby wyświetlić obraz. Atrybut 'src' \*\*\* podaje nazwę obrazu.

Znacznik „<img>” nie ma znacznika końcowego.

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

**Test:** Kliknij przycisk **Run**.

Obraz "love.png" pojawia się na Twojej stronie internetowej.

\--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Alternatywny (Alt) tekst**</span> to opis obrazu i jest ważny w projektowaniu stron internetowych, aby opisywać obrazy osobom, które nie są w stanie ich zobaczyć. Tekst nie pojawia się na stronie internetowej, ale jest odczytywany na głos przez czytniki ekranu.
</p>

\--- task ---

Dodaj atrybut "alt", aby dostarczyć tekst alternatywny dla osób, które nie mogą zobaczyć obrazu.

Możesz skopiować opis swojego obrazu i wkleić go do kodu: "Wyraz twarzy miłości"

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

Dodaj akapit tekstu w tagach "<p> </p>", aby opisać, jak narysować wyraz twarzy anime miłości.

Możesz skopiować akapit i wkleić go do swojego kodu:
„<p> To, aby twoja postać z anime wyglądała tak, jakby była w miłości, zastąp oczy dwoma zaokrąglonymi sercami. Możesz dodać trzy kolejne serca do środka, aby uzyskać zabawny efekt.</p>"

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

Znacznik „<strong>” tworzy ważny tekst **pogrubiony**.

\--- task ---

Dodaj tagi "<strong>" wokół słowa "miłość":

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

**Test:** Kliknij przycisk **Run**.

Instrukcje pojawiają się pod Twoim obrazem, a słowo **love** jest pogrubione.

<iframe src="https://editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-3" width="500" height="750" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
--- /task ---

