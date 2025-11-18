## Styl swojej strony

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

Użyłeś kodu HTML, aby dodać znaczniki do swojej strony internetowej.

Teraz nadszedł czas, aby użyć CSS, aby dodać style do swojej strony.

Ten krok pokazuje, jak zmienić kolory, czcionki i układ na swojej stronie internetowej.

</div>
<div>
<iframe src="https://editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-4" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Kaskadowe arkusze stylów (CSS)**</span> to język, którego używasz, aby powiedzieć przeglądarce internetowej, jak powinna wyglądać Twoja strona, który obejmuje pozycjonowanie, kolory i czcionki. Nazywamy to stylem.
</p>

Każda **reguła** w CSS składa się z dwóch części: **Selektor** i **deklaracja**.

**Selektor** to część HTML, którą chcesz stylizować. W tym przykładzie jest to "h1".

<div style="background-color:#2d2d2d; padding: 1em;">
  <pre><span style="color:#000; background-color:#d2d2d2; font-family: Consolas, Monaco, 'Andale Mono', 'Ubuntu Mono', monospace; font-size: 1em">h1 </span
  ><span style=" color:#ccc;  font-family: Consolas, Monaco, 'Andale Mono', 'Ubuntu Mono', monospace; font-size: 1em">{
  color: blue;
  font-size: 12px;
}</span></pre>
</div>
<br/>

**Deklaracja** jest w nawiasach klamrowych "{}". Zawiera instrukcje dotyczące stylów, które powinny być używane.

<div style="background-color:#2d2d2d; padding: 1em;">
<pre><span style="color:#ccc; font-family: Consolas, Monaco, 'Andale Mono', 'Ubuntu Mono', monospace; font-size: 1em">h1 </span
><span style=" color:#000; background-color:#d2d2d2; font-family: Consolas, Monaco, 'Andale Mono', 'Ubuntu Mono', monospace; font-size: 1em">{
  color: blue;
  font-size: 12px;
}</span></pre>
</div>
<br/>

### Połącz plik CSS

Projekt startowy zawiera pliki CSS, które zawierają zestaw użytecznych zasad.

\--- task ---

Rozwiń sekcję „<head>” swojego kodu, aby móc wyświetlić kod wewnątrz niego.

![mysz kliknie mały trójkąt obok liczby linii 3, aby zwinąć kod głowy.](images/step_2_collapse.gif)

\--- /task ---

\--- task ---

U dołu sekcji „<head> </head>” znajdują się linki do dwóch arkuszy stylów CSS, które są obecnie komentowane, aby były ignorowane przez przeglądarkę internetową.

Usuń strzałki "<!--" i "-->" z początku i na końcu obu linii kodu łącza:

**Przed**

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 21
line_highlights: 23-24
-----------------------------------------------------------

```
<!-- dołącz plik stylu CSS -->

<!-- <link href="style.css" rel="stylesheet" type="text/css" /> -->
<!-- <link href="candy.css" rel="stylesheet" type="text/css" /> -->
```

  </head>

\--- /code ---

**Po**

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 21
line_highlights: 23-24
-----------------------------------------------------------

```
<!-- dołącz plik stylu CSS -->


<link href="style.css" rel="stylesheet" type="text/css" /> <link href="candy.css" rel="stylesheet" type="text/css" />
```

  </head>

\--- /code ---
\--- /task ---

\--- task ---

**Test:** Kliknij przycisk **Run**.

Elementy HTML mają domyślne style przeglądarki, które widziałeś po napisaniu kodu HTML.

Spójrz na swoją stronę internetową w prawym panelu. Zauważ, że style i układ wydruku uległy zmianie.

**Wskazówka:** aby zwinąć sekcję „<head>” po zobaczeniu zmiany, kliknij strzałkę obok niej.

\--- /task ---

\--- task ---

Kliknij ikonę "Pliki projektu" w Edytorze kodu, a następnie wybierz plik "style.css" u góry otwarty w nowej karcie.

![Edytor kodu z podświetloną ikoną plików projektu](images/select-file.png)

![Edytor kodu z podświetlonym plikiem style.css](images/select-style.png)

Ten plik CSS zawiera cały kod CSS dla Twojego projektu. Podczas tworzenia strony internetowej dowiesz się o niektórych kluczowych częściach tego pliku CSS.

Kiedy dodasz stylizację CSS do **elementu**, zastosuje ona tę stylizację do każdego pojedynczego elementu na stronie, który ma ten sam tag.

**Znajdź:** Przewiń w dół i znajdź regułę, która kontroluje styl „<h2>”.

## --- code ---

language: css
filename: style.css
line_numbers: true
line_number_start: 109
line_highlights: 109-113
-------------------------------------------------------------

h2 {
font: var(--title-font); /\* Font style stored in the title-font variable _/
text-align: left; /_ Align the text _/
padding: 1.5rem; /_ Add some space all around the heading \*/
}

\--- /code ---

Ta reguła określa, która czcionka powinna być używana, jak tekst powinien być wyrównany i ile miejsca powinno być wokół nagłówka.

\--- /task ---

\--- task ---

W tej chwili nagłówek „<h2>” jest wyrównany w lewo.

Zmień właściwość "text-align" reguły "h2" na "center".

## --- code ---

language: css
filename: style.css
line_numbers: true
line_number_start: 109
line_highlights: 111
---------------------------------------------------------

h2 {
font: var(--title-font); /\* Font style stored in the title-font variable _/
text-align: center; /_ Align the text _/
padding: 1.5rem; /_ Add some space all around the heading \*/
}

\--- /code ---

\--- /task ---

\--- task ---

**Test:** Kliknij przycisk **Run**.

Spójrz na swoją stronę internetową i upewnij się, że tekst „Wyrażenia twarzy” jest wyśrodkowany.

**Debugowanie:** Sprawdź pisownię słowa „center”. HTML używa pisowni amerykańskiej (US) języka angielskiego.

<iframe src="https://editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-4" width="500" height="750" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>

\--- /task ---

