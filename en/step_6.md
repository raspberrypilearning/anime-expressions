## Colours and fonts

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

In this step you will try out different colour palette and font choices.

</div>
<div>
<iframe src="https://trinket.io/embed/html/cff6fa893b?outputOnly=true" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>
</div>

Now that you have started to add custom classes to your code, you will have noticed that colour is being added to the page. In CSS you can create a colour palette for your webpage using **variables**. 

CSS variables start with two dashes: `--primary`. 

Colours are specified using hexadecimal notation (hex) and begin with '#'. There are lots of web sites where you can find hex colours to use. 

--- task ---

Go to your `candy.css` file. This file sets the colour variables for the Candy colour palette.

In the Candy colour palette, the `--primary` variable is set to `#ebeaeb`, a pale grey.

--- code ---
---
language: CSS
filename: candy.css
line_numbers: true
line_number_start: 2
line_highlights: 5
---
/* Candy colour palette & fonts */

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

**Tip:** CSS uses different comment markers to HTML. Multi-line comments start with `/*` and end with `*/`. The browser ignores code that is inside the comment markers. `/* Candy colour palette & fonts */` is an example of a CSS comment.

--- /task ---

You can also use variables for fonts. The `--header-font` is set to `3rem 'Fredoka One', cursive;`

`3rem` means that this font should be 3 times the normal font size. 

`'Fredoka One', cursive` means that the browser should use the 'Fredoka One' font if it can, and if it isn't available it should use the **fallback font**, which is `cursive`. 

[[[web-fonts]]]

--- task ---

**Find** the variables that set the fonts for your web page:

--- code ---
---
language: CSS
filename: candy.css
line_numbers: true
line_number_start: 16
line_highlights: 16-19
---

  --body-font: 1rem 'Verdana', sans-serif;
  --header-font: 3rem 'Fredoka One', cursive;
  --title-font: 2rem 'Fredoka One', cursive;
  --quote-font: lighter 1.5rem 'Chewy', cursive;
}

--- /code ---

--- /task ---

The `primary` colours are designed to be used the most in the main content of the page, followed by the `secondary` and then `tertiary` colours. This means that you can easily design new colour palettes and switch between them. 

The starter project also includes a vivid colour palette file called `vivid.css`. 

--- task ---

**Find** the `vivid.css` file. 

Notice that the colour and font variables have the same name but that the colours and fonts used are different in this colour palette. 

--- code ---
---
language: CSS
filename: vivid.css
line_numbers: true
line_number_start: 1
---

/* Vivid colour palette & fonts */

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

Go to `index.html` and change the CSS link code to link to the `vivid.css` file: 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 23
line_highlights: 24
---   
    <!-- Include CSS style file -->

    <link href="style.css" rel="stylesheet" type="text/css" />
    <link href="vivid.css" rel="stylesheet" type="text/css" />
  </head>

--- /code ---

--- /task ---

--- task ---

**Test:** Make sure your web page is now using the brighter colours and different fonts. 

<iframe src="https://trinket.io/embed/html/cff6fa893b?outputOnly=true" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

--- /task ---