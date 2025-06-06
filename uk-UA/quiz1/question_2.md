--- question ---

---
legend: Питання 2 з 3
---

Класи CSS можна застосувати до коду HTML. Вони визначають, який вигляд матиме вміст у веббраузері.

Нижче наведено код CSS для стилізації підзаголовка. Який рядок коду потрібно змінити, щоб підзаголовок відображався праворуч?

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 1
line_highlights: 
---  

h2 {
    font: var(--title-font); 
    text-align: left; 
    padding: 1.5rem; 
}

--- /code ---

--- choices ---

- ( ) 1

  --- feedback ---

Спробуй ще раз. У першому рядку вказано, що **селектором**, до якого застосовується правило, є тег `h2`.

--- /feedback ---

- ( ) 2

  --- feedback ---

Не зовсім так. У другому рядку говориться, що шрифт для елементів із тегом `h2` зберігається у **змінній** `--title-font`.

--- /feedback ---

- (x) 3

  --- feedback ---

  Правильно! Третій рядок дозволяє змінити вирівнювання тексту. Якщо змінити `left` на `right`, текст буде вирівняно по правій стороні.

  --- /feedback ---

- ( ) 4

  --- feedback ---

  Спробуй ще раз. Четвертий рядок регулює простір навколо підзаголовка.

  --- /feedback ---

--- /choices ---

--- /question ---
