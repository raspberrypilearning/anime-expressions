## Style with classes

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

This step shows you how to add classes to customise the styles on your page. 

</div>
<div>
<iframe src="https://trinket.io/embed/html/b72e02e1d2?outputOnly=true" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>
</div>

If you want to apply styling to specific elements, you can create a **class** in a CSS file. You can then add a `class=` **attribute** to an element in your HTML code to let the browser know what styling should be applied. 
  
The class styling overrides any element styling that has already been applied. Notice the changes take place as you add the classes to your code.

--- task ---

Your CSS file has a custom CSS class called `border-bottom`. This class adds a thick, solid-coloured line border to the bottom of any HTML element that uses it.

Go to your `index.html` file and find your `header`. 

Add `class="border-bottom"` to the right inside your `header` tag. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 27
line_highlights: 29
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
line_number_start: 55
line_highlights: 56
---
  <!-- Webpage footer -->
    <footer class="border-top">

--- /code ---

--- /task ---

The `primary` class sets a contrasting background and text colour that is designed to be used for most of the main content. The `secondary` and `tertiary` classes set additional colour combinations that look good with the primary colours.

--- task ---

Add the `secondary` class to your `footer` code to apply a different colour background to your footer. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 55
line_highlights: 56
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
line_number_start: 33
line_highlights: 34
---
    <!-- The main content for the webpage goes between the main tags -->
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
line_number_start: 28
line_highlights: 29
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
line_number_start: 33
line_highlights: 35, 37
---
    <!-- The main content for the webpage goes between the main tags -->
    <main class="primary">
      <section class="tertiary">
        <h2>Facial expressions</h2>
        <p class="xcenter">Take a look at these facial expressions and try them in your own drawings.</p>
      </section>

--- /code ---

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Webpages can be viewed on many different devices and should be <span style="color: #0faeb0">**responsive**</span> to each device. This means that if a user views your site on a mobile phone, it should respond to a smaller screen and if they view it on a desktop PC it should respond to a larger screen. 
</p>

As well as changing colours, fonts, and borders, CSS can also be used to change the layout on the page. 

--- task ---

Find the **second** `<section>`. 

Add `class="wrap"` to the `<section>` tag.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 40
---
   <!-- The first drawing and instructions goes here -->
<section class="wrap">
  <img src="love.png" alt="The love facial expression.">
  <p>To make your anime character look like they are in love, replace the eyes with two rounded hearts. You can add three more hearts inside for a fun effect.</p>
</section>

--- /code ---

--- /task ---

You can also add coloured borders in different styles to HTML elements. The `dashed-border` class in the style file creates a dashed border. 

--- task ---

Add the `dashed-border` class to the `<img>`. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---
<!-- The first drawing and instructions goes here -->
<section class="wrap">
  <img class="dashed-border" src="love.png" alt="The love facial expression.">
  <p>To make your anime character look like they are in love, replace the eyes with two rounded hearts. You can add three more hearts inside for a fun effect.</p>
</section>

--- /code ---

--- /task ---

You can also make the corners of an element rounded by using the `rounded` class. 

--- task ---

Add the `rounded` class to the `<img>`. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---
<!-- The first drawing and instructions goes here -->
<section class="wrap">
  <img class="dashed-border rounded" src="love.png" alt="The love facial expression.">
  <p>To make your anime character look like they are in love, replace the eyes with two rounded hearts. You can add three more hearts inside for a fun effect.</p>
</section>

--- /code ---

--- /task ---

--- task ---

**Test:** Drag the bar between the text editor and your webpage and make the webpage narrower. 

The text should move below the image. This is the layout for users who view the webpage on a mobile phone. 

Drag the bar back after you test it, so you can see the image and text side-by-side. 

![In Trinket, the vertical space between the two panes is dragged from left to right to show that the webpage adjusts for smaller screens.](images/drag-window.gif)

--- /task ---
