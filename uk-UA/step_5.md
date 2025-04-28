## Стиль із класами

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

Цей крок показує, як додати класи, щоб налаштувати стилі на твоїй сторінці.

</div>
<div>
<iframe src="https://editor.raspberrypi.org/uk-UA/embed/viewer/anime-expressions-step-5" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

Якщо ти хочеш застосувати стилі до певних елементів, ти можеш створити **клас** у файлі CSS. Потім ти можеш додати до елемента у своєму HTML-коді фразу `class=` **атрибут**, щоб повідомити браузеру, який стиль слід застосувати.

Стиль класу замінює будь-який стиль елемента, який уже було застосовано. Зверни увагу, що зміни відбуваються, коли ти додаєш класи до свого коду.

--- task ---

У файлі CSS є спеціальний клас CSS під назвою `border-bottom` («межа-низ»). Цей клас додає товсту межу суцільного кольору внизу будь-якого елемента HTML, який його використовує.

Перейди до файлу `index.html` і знайди свій заголовок `header`.

У тегу `header` додай `class="border-bottom"` після слова `header`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 27
line_highlights: 29
---
  <body>
    <!-- Тут буде код заголовку сторінки -->
    <header class="border-bottom">
      <h1>Малюй аніме зі мною</h1>
    </header>

--- /code ---

--- /task ---

--- task ---

Додай клас `border-top` («межа-верх») до коду `footer`, щоб отримати товсту межу у верхній частині нижнього колонтитула.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 55
line_highlights: 56
---
    <!-- Нижній колонтитул сторінки -->
    <footer class="border-top">

--- /code ---

--- /task ---

Клас `primary` («основний») встановлює контрастний фон і колір тексту для більшості основного вмісту.

Клас `secondary` («вторинний») встановлює додаткову палітру кольорів, яка пасує до кольорів у класі `primary`.

--- task ---

Додай клас `secondary` до свого коду `footer`, щоб застосувати до нижнього колонтитула фон іншого кольору.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 55
line_highlights: 56
---
    <!-- Нижній колонтитул сторінки -->
    <footer class="border-top secondary">

--- /code ---

--- /task ---

--- task ---

Додай `class="primary"` до `<main>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 34
---
    <!-- Між тегами main розміщуємо основний вміст сторінки -->
    <main class="primary">

--- /code ---

--- /task ---

--- task ---

Додай клас `secondary` до `<header>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 28
line_highlights: 29
---
    <!-- Тут буде код заголовку сторінки -->
    <header class="border-bottom secondary">
--- /code ---

--- /task ---

Клас `tertiary` («третинний») встановлює додаткову палітру кольорів, яка пасує до кольорів у класах `primary` і `secondary`.

--- task ---

Додай `class="tertiary"` до **першого** елемента `<section>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 35
---
    <!-- Між тегами main розміщуємо основний вміст сторінки -->
    <main class="primary">
      <section class="tertiary">
        <h2>Вирази обличчя</h2>
        <p class="xcenter">Подивися на ці вирази обличчя та спробуй повторити їх у своїх малюнках.</p>
      </section>

--- /code ---

Клас `xcenter` у твоєму файлі CSS вирівнює елементи горизонтально по всій сторінці.

--- /task ---

--- task ---

Додай `class="xcenter"` до `<p>` у тій же секції.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 37
---
    <!-- Між тегами main розміщуємо основний вміст сторінки -->
    <main class="primary">
      <section class="tertiary">
        <h2>Вирази обличчя</h2>
        <p class="xcenter">Подивися на ці вирази обличчя та спробуй повторити їх у своїх малюнках.</p>
      </section>

--- /code ---

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Вебсторінки можна переглядати на багатьох різних пристроях, і вони повинні <span style="color: #0faeb0">**підлаштовуватися**</span> під кожний пристрій. Це означає, що якщо користувач переглядає твою сторінку на мобільному телефоні, вона має підлаштовуватися під менший екран, а якщо він переглядає її на настільному ПК, вона має підлаштовуватися під більший екран. 
</p>

CSS може змінювати макет сторінки, а також змінювати кольори, шрифти й межі.

--- task ---

Знайди **другий** елемент `<section>`.

Додай `class="wrap"` до тегу `<section>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 40
---
    <!-- Тут буде перший малюнок і вказівки -->
    <section class="wrap">
      <img src="love.png" alt="Закоханий вираз обличчя.">
      <p>Щоб твій аніме-персонаж виглядав закоханим, заміни очі на два сердечка. Щоб отримати ще цікавіший ефект, додай всередину три менших сердечка.</p>
    </section>

--- /code ---

--- /task ---

Ти також можеш додавати кольорові межі в різних стилях до елементів HTML. Клас `dashed-border` у файлі стилю створює пунктирну межу.

--- task ---

Додай клас `dashed-border` до `<img>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---
    <!-- Тут буде перший малюнок і вказівки -->
    <section class="wrap">
      <img class="dashed-border" src="love.png" alt="Закоханий вираз обличчя.">
      <p>Щоб твій аніме-персонаж виглядав закоханим, заміни очі на два сердечка. Щоб отримати ще цікавіший ефект, додай всередину три менших сердечка.</p>
    </section>

--- /code ---

--- /task ---

Ти можеш зробити кути елемента округленими за допомогою класу `rounded`.

--- task ---

Додай клас `rounded` до `<img>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---
    <!-- Тут буде перший малюнок і вказівки -->
    <section class="wrap">
      <img class="dashed-border rounded" src="love.png" alt="Закоханий вираз обличчя.">
      <p>Щоб твій аніме-персонаж виглядав закоханим, заміни очі на два сердечка. Щоб отримати ще цікавіший ефект, додай всередину три менших сердечка.</p>
    </section>

--- /code ---

--- /task ---

--- task ---

**Протестуй:** натисни на кнопку **Run**.

Перетягни барʼєр між текстовим редактором і вебсторінкою, щоб зробити її вужчою.

Текст повинен переміститися під зображення. Це макет для користувачів, які переглядають сторінку на мобільному телефоні.

Після перевірки перетягни барʼєр назад, щоб зображення й текст були поруч.

![У редакторі вертикальний простір між двома панелями перетягується зліва направо, щоб показати, що вебсторінка адаптується до менших екранів.](images/drag-window.gif)

--- /task ---
