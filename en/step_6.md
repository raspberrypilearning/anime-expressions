## Colours and fonts

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

In this step you will try out a different colour palette and font choices.

</div>
<div>
<iframe src="https://trinket.io/embed/html/b72e02e1d2?outputOnly=true" width="350" height="700" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>
</div>

Now that you have started to add custom classes to your code, you will have noticed that colour is being added to the page. In CSS you can create a colour palette for your webpage using **variables**. 

--- task ---

Go to your style.css file and take a look at lines 24 onwards. 

CSS variables start with two dashes. 

`--primary` 

--- code ---
---
language: html
filename: style.css
line_numbers: true
line_number_start: 24
line_highlights: 27-36
---
/* Candy colour palette & fonts */

:root {
  --primary: #ebeaeb;
  --onprimary: #625d61;
  --secondary: #f5bdd5;
  --onsecondary: #1D3D58;
  --tertiary: #b5a9b2;
  --ontertiary: #422215;
  --page: #ffffff;
  --onpage: #000000;
  --detail: #e697b9;
  --detail2: #415a89;

  --body-font: 1rem 'Verdana', sans-serif;
  --header-font: 3rem 'Fredoka One', cursive;
  --title-font: 2rem 'Fredoka One', cursive;
  --quote-font: lighter 1.5rem 'Chewy', cursive;
}

--- /code ---

--- /task ---