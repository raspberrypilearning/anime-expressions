## Кольори та шрифти

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

На цьому кроці ти спробуєш різні палітри кольорів і шрифти.

</div>
<div>
<iframe src="https://editor.raspberrypi.org/uk-UA/embed/viewer/anime-expressions-step-6" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

Ми почали додавати власні класи до нашого коду, і ти, мабуть, бачиш, що на сторінці почали зʼявлятися кольори. У CSS ти можеш використовувати **змінні** для створення палітри кольорів для вебсторінки.

Змінні CSS починаються з двох рисочок: `--primary`.

Кольори вказуються в шістнадцятковому форматі (hex) і починаються з «#». Є багато вебсайтів, де можна знайти шістнадцяткові кольори для своїх проєктів.

--- task ---

Перейди до файлу `candy.css`. Цей файл встановлює змінні кольорів для пастельної палітри.

У пастельній палітрі змінна `--primary` має значення `#ebeaeb` — блідо-сірий колір.

--- code ---
---
language: CSS
filename: candy.css
line_numbers: true
line_number_start: 1
line_highlights: 4
---
/* Палітра пастельних кольорів і шрифтів */

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

**Порада:** у CSS використовуються інші позначки коментарів, ніж у HTML. Коментарі на декілька рядків починаються з `/*` і закінчуються `*/`. Браузер ігнорує код, який знаходиться всередині позначок коментарів.

`/* Палітра пастельних кольорів і шрифтів */` — це приклад коментаря в CSS.

--- /task ---

Ти також можеш використовувати змінні для шрифтів. Шрифт заголовка `--header-font` має значення `3rem 'Fredoka One', cursive;`

`3rem` означає, що розмір цього шрифту має бути втричі більшим за звичайний.

`'Fredoka One', cursive` означає, що браузер має використовувати шрифт 'Fredoka One', якщо можливо. Якщо цей шрифт недоступний, браузер має використовувати **резервний шрифт** `cursive` (курсив).

[[[web-fonts]]]

--- task ---

**Знайди** змінні, які встановлюють шрифти для твоєї вебсторінки.

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

Основні кольори (`primary`) використовуються в основному вмісті сторінки найчастіше. Потім йдуть вторинні (`secondary`), а потім третинні кольори (`tertiary`). Це означає, що ти можеш легко створювати нові палітри кольорів та перемикатися між ними.

Початковий проєкт також містить файл палітри яскравих кольорів під назвою `vivid.css`.

--- task ---

**Знайди** файл `vivid.css`.

Зверни увагу, що змінні кольорів та шрифтів мають ті самі назви, що й у файлі `candy.css`, але кольори та шрифти в цій палітрі інші.

--- code ---
---
language: CSS
filename: vivid.css
line_numbers: true
line_number_start: 1
---

/* Палітра яскравих кольорів і шрифтів */

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

Перейди до `index.html` і зміни код посилання CSS на файл `vivid.css`:

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 21
line_highlights: 24
---   
    <!-- Посилання на файл стилів CSS -->

    <link href="style.css" rel="stylesheet" type="text/css" />
    <link href="vivid.css" rel="stylesheet" type="text/css" />

--- /code ---

--- /task ---

--- task ---

**Протестуй:** натисни на кнопку **Run**.

Переконайся, що твоя вебсторінка тепер використовує яскравіші кольори та інші шрифти, визначені у файлі `vivid.css`.

<iframe src="https://editor.raspberrypi.org/uk-UA/embed/viewer/anime-expressions-step-6" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>

--- /task ---
