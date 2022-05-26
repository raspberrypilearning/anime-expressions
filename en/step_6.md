## Colours and fonts

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

In this step you will try out different colour palette and font choices.

</div>
<div>
<iframe src="https://trinket.io/embed/html/cff6fa893b?outputOnly=true" width="350" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>
</div>

Now that you have started to add custom classes to your code, you will have noticed that colour is being added to the page. In CSS you can create a colour palette for your webpage using **variables**. 

CSS variables start with two dashes: `--primary`. 

Colours are specified using hexadecimal notation (hex) and begin with '#'. There are lots of web sites where you can find hex colours to use. 

--- task ---

Go to your `style.css` file and take a look at lines 24 onwards. 

In the Candy colour palette, the `--primary` variable is set to `#ebeaeb`, a pale grey.

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
  --onsecondary: #1d3d58;
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

You can also use variables for fonts. The `--header-font` is set to `3rem 'Fredoka One', cursive;`

`3rem` means that this font should be 3 times the normal font size. 

`'Fredoka One', cursive` means that the browser should use the 'Fredoka One' font if it can, and if it isn't available it should use the **fallback font**, which is `cursive`. 

--- collapse ---
---
title: Fonts for the web
---

Web designers carefully consider the font styles for their website. 

The **three** most common categories of font are:

+ Library fonts
+ Web safe fonts
+ Fallback fonts

**Library fonts** are typically imported from a third party library such as [Google Fonts](https://fonts.google.com/). Companies will sometimes pay a fee to use a font as part of their website branding. 

**Web safe fonts** are standard fonts that should be available through any web browser. However, you can never be 100% sure that this is the case. Here is a list of web safe fonts:

+ Arial 
+ Verdana 
+ Helvetica 
+ Tahoma 
+ Trebuchet MS 
+ Times New Roman 
+ Georgia 
+ Garamond 
+ Courier New 
+ Brush Script MT 

**Fallback fonts** are generic font families that are used to match the styling that the web designer would like to use. The main font families are:

+ Serif - a font style typically used in print publishing, letters have tiny decorative edges called 'serifs'
+ Sans-serif - a clean, screen readable font without the decorative edges
+ Monospace - a font where each character uses the same width of space
+ Cursive - a handwriting font
+ Fantasy - a decorative font typically used for big headings

If a fallback font isn't listed then the web browser will use the browsers default font which is typically Times New Roman. 

--- /collapse ---

--- task ---

**Find** the variables that set the fonts for your web page:

--- code ---
---
language: html
filename: style.css
line_numbers: true
line_number_start: 40
line_highlights: 41-44
---

  --body-font: 1rem 'Verdana', sans-serif;
  --header-font: 3rem 'Fredoka One', cursive;
  --title-font: 2rem 'Fredoka One', cursive;
  --quote-font: lighter 1.5rem 'Chewy', cursive;
}

--- /code ---

--- /task ---

CSS uses different comment markers to HTML. Multi-line comments start with `/*` and end with `*/`. The browser ignores code that is inside the comment markers.

The starter project also includes a vivid colour palette with different fonts. 

--- task ---

Add begin `/*` and end `*/` comment markers to comment out the candy colour palette.  

--- code ---
---
language: html
filename: style.css
line_numbers: true
line_number_start: 24
line_highlights: 25, 42
---
/* Candy colour palette & fonts */
/*
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

  --body-font: 1rem 'Verdana', sans-serif;
  --header-font: 3rem 'Fredoka One', cursive;
  --title-font: 2rem 'Fredoka One', cursive;
  --quote-font: lighter 1.5rem 'Chewy', cursive;
}*/

--- /code ---

Note how the styling has been removed from your webpage. 

--- /task --- 

--- task ---

**Find** the vivid colour palette and delete the begin and end comment markers around it. 

--- code ---
---
language: html
filename: style.css
line_numbers: true
line_number_start: 45
line_highlights: 46, 63
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

**Test:** Make sure your web page is now using the brighter colours and different fonts. 

--- /task ---