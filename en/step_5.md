## Style with classes

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

In this step you will add classes to customise the styles on your page.

</div>
<div>
<iframe src="https://trinket.io/embed/html/b72e02e1d2?outputOnly=true" width="350" height="700" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>
</div>

If you want to apply styling to specific elements, you can create a **class** in a CSS file and then add a `class=` **attribute** to an element in your HTML code to let the browser know what styling should be applied. 
  
The class styling will override any element styling that has already been applied. 

--- task ---

Your CSS file has a custom CSS class called `border-bottom` which adds a thick, solid coloured line border to the bottom of any HTML element that uses it.

Go to your `index.html` file and find your `header`. 

Add `class="border-bottom"` to the right of `header` text. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 26
line_highlights: 28
---
  <body>
    <!-- The page header code goes here -->
    <header class="border-bottom">
      <h1>Draw anime with me</h1>
    </header>

--- /code ---

--- /task ---

--- task ---

Add the `border-top` class to your `footer` code to apply a thick border to the top of your footer. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 26
line_highlights: 27
---
  <!-- Webpage footer -->
    <footer class="border-top">

--- /code ---

--- /task ---

The `primary`, `secondary` and `tertiary` classes set different combinations of contrasting background and text colour. 

--- task ---

Add the `secondary` class to your `footer` code to apply a different colour background to your footer. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 26
line_highlights: 27
---
  <!-- Webpage footer -->
    <footer class="border-top secondary">

--- /code ---

--- /task ---

--- task ---

Add `class=primary` to `<main>`:

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 32
line_highlights: 33
---
    <!-- The main content for the web page goes between the main tags -->
    <main class="primary">

--- /code ---

--- /task ---

--- task ---

Add `secondary` to `<header>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 27
line_highlights: 28
---
    <!-- The page header code goes here -->
    <header class="border-bottom secondary">

--- /code ---

--- /task ---

The `xcenter` class in your CSS file aligns items horizontally across the page. 

--- task ---

Add `class="tertiary"` to the **first** `<section>` element.

Also, add `class="xcenter"` to the `<p>` in the same section. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 32
line_highlights: 34, 36
---
    <!-- The main content for the web page goes between the main tags -->
    <main class="primary">
      <section class="tertiary">
        <h2>Facial expressions</h2>
        <p class="xcenter">Take a look at these facial expressions and try them in your own drawings.</p>
      </section>

--- /code ---

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Web pages can be viewed on many different devices and should be <span style="color: #0faeb0">**responsive**</span> to each device. This means that if a user views your site on a mobile phone, it should respond to a smaller screen and if they view it on a desktop PC it should respond to a larger screen. 
</p>

As well as changing colours, fonts and borders, CSS can also be used to change the layout on the page. 

--- task ---

Find the **second** `<section>`. 

Add `class="wrap"` to the `<section>` tag.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 42
---
   <!-- The first drawing and instructions goes here -->
<section class="wrap">
  <img src="love.png" alt="The love facial expression.">
  <p>To make your anime character look like they are in love, replace the eyes with two rounded hearts. Remember to add highlight to the corners to create a better effect.</p>
</section>

--- /code ---

--- /task ---

--- task ---

**Test:** Drag the bar between the text editor and your web page and make the web page narrower. 

The text should move below the image. This is the layout that users with a mobile phone in portrait mode will see. 

Drag the bar back after testing so you can see the image and text side-by side. 

<mark>Add animated gif</mark>

--- /task ---

Now that you have started to add custom classes to your code, you will have noticed that colour is being added to the page. In CSS you can create a colour palette for your webpage using variables. 

--- task ---

Go to your style.css file and take a look at lines 24 onwards. This includes a 

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