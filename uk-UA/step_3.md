## Додай вираз обличчя

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
На цьому кроці додай перший малюнок та вказівки до своєї сторінки.</div>
<div>
<iframe src="https://editor.raspberrypi.org/uk-UA/embed/viewer/anime-expressions-step-3" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

Перш за все, створи секцію для кожного виразу обличчя.

--- task ---

Знайди коментар `<!-- Тут буде перший малюнок і вказівки -->`.

Додай теги `<section></section>` для свого першого малюнку та вказівок.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 40-42
---
    <main>
      <section>
        <h2>Вирази обличчя</h2>
        <p>Подивися на ці вирази обличчя та спробуй повторити їх у своїх малюнках.</p>
      </section>
      
      <!-- Тут буде перший малюнок і вказівки -->     
      <section>
          
      </section> 

--- /code ---

--- /task ---

Твій стартовий проєкт містить зображення, які ти можеш використовувати в цьому проєкті. Щоб розмістити на вебсторінці зображення, ти маєш знати назву файлу. Спочатку додай зображення під назвою `love.png` (з англійської «любов»).

--- task ---

У новій секції додай тег `<img>`, щоб показати зображення. **Атрибут** `src` вказує назву зображення.

Тег `<img>` не потребує кінцевого тегу.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---
      <!-- Тут буде перший малюнок і вказівки -->     
      <section>
        <img src="love.png">
      </section> 

--- /code ---

--- /task ---

--- task ---

**Протестуй:** натисни на кнопку **Run**.

На твоїй вебсторінці з’явиться зображення `love.png`.

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Альтернативний текст (альт-текст)**</span> — це опис зображення. Він є важливою частиною доступної веброзробки, оскільки описує зображення для людей, які не можуть їх побачити. Текст не видно на вебсторінці, але його читають вголос спеціальні програми для зчитування з екрана.
</p>

--- task ---

За допомогою атрибуту `alt` додай альтернативний текст для людей, які не можуть переглядати зображення.

Ти можеш скопіювати опис свого зображення та вставити його у свій код: `Закоханий вираз обличчя.`

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---
      <!-- Тут буде перший малюнок і вказівки -->     
      <section>
        <img src="love.png" alt="Закоханий вираз обличчя.">
      </section> 

--- /code ---

--- /task ---

--- task ---

Всередину тегів `<p></p>` додай абзац з описом, як намалювати закоханий вираз обличчя у стилі аніме.

Ти можеш скопіювати цей абзац і вставити його у свій код:
`<p>Щоб твій аніме-персонаж виглядав закоханим, заміни очі на два сердечка. Щоб отримати ще цікавіший ефект, додай всередину три менших сердечка.</p>`

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 42
---   
      <!-- Тут буде перший малюнок і вказівки -->     
      <section>
        <img src="love.png" alt="Закоханий вираз обличчя.">
        <p>Щоб твій аніме-персонаж виглядав закоханим, заміни очі на два сердечка. Щоб отримати ще цікавіший ефект, додай всередину три менших сердечка.</p>
      </section> 

--- /code ---

--- /task ---

Тег `<strong>` виділяє важливий текст **жирним**.

--- task ---

Додай теги `<strong>` навколо слова «закоханим»:

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 42
---  
      <!-- Тут буде перший малюнок і вказівки -->     
      <section>
        <img src="love.png" alt="Закоханий вираз обличчя.">
        <p>Щоб твій аніме-персонаж виглядав <strong>закоханим</strong>, заміни очі на два сердечка. Щоб отримати ще цікавіший ефект, додай всередину три менших сердечка.</p>
      </section> 

--- /code ---

--- /task ---

--- task ---

**Протестуй:** натисни на кнопку **Run**.

Вказівки з’являться під твоїм зображенням, а слово **закоханим** виділено жирним шрифтом.

<iframe src="https://editor.raspberrypi.org/uk-UA/embed/viewer/anime-expressions-step-3" width="500" height="750" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
--- /task ---

