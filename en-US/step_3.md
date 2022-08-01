## Add a facial expression

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In this step, add the first drawing and instruction to your webpage.
</div>
<div>
<iframe src="https://trinket.io/embed/html/893f1c44ad?outputOnly=true" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>
</div>

First, create a section for each facial expression on the webpage.

--- task ---

Find the comment `<!-- The first drawing and instructions go here -->`.

Add in the `<section></section>` tags for your first drawing and instruction content.

--- code ---
---
language: html filename: index.html line_numbers: true line_number_start: 33
line_highlights: 40-42
---

    <main>
    <section>
## Facial expressions

Take a look at these facial expressions and try them in your own drawings.</section>
       
      <!-- The first drawing and instructions go here -->     
      <section> </section>

--- /code ---

--- /task ---

Your starter project contains images to use in this project. To include an image on a webpage, you need to know the filename. First, add an image called `love.png`.

--- task ---

Inside your new section, add an `<img>` tag to display an image. The `src` **attribute** gives the name of the image.

 The `<img>` tag doesn't have an end tag.

--- code ---
---
language: html filename: index.html line_numbers: true line_number_start: 39
line_highlights: 41
---
      <!-- The first drawing and instructions go here -->     
      <section> 

![](love.png) </section>

--- /code ---

--- /task ---

--- task ---

**Test:** The `love.png` image appears on your webpage.

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Alternative (Alt) text**</span> is a description of an image and is important in accessible web design to describe images to people who are unable to see them. The text does not appear on the webpage but it is read aloud by screen readers.
</p>

--- task ---

Add the `alt` property to provide alternative text for people who cannot view the image.

You can copy the description of your image and paste it into your code: `The love facial expression.`

--- code ---
---
language: html filename: index.html line_numbers: true line_number_start: 39
line_highlights: 41
---   
      <!-- The first drawing and instructions go here -->     
      <section> 

![The love facial expression.](love.png) </section>

--- /code ---

--- /task ---

--- task ---

Add a paragraph of text in `<p></p>` tags to describe how to draw the love anime facial expression.

You can copy the paragraph and paste it into your code: `<p>To make your anime character look like they are in love, replace the eyes with two rounded hearts. Remember to add highlight to the corners to create a better effect.</p>`

--- code ---
---
language: html filename: index.html line_numbers: true line_number_start: 39
line_highlights: 42
---   
      <!-- The first drawing and instructions go here -->     
      <section> 

![The love facial expression.](love.png)

To make your anime character look like they are in love, replace the eyes with two rounded hearts. Remember to add highlight to the corners to create a better effect.</section>

--- /code ---

--- /task ---

The `<strong>` tag makes important text **bold**.

--- task ---

Add `<strong>` tags around the word 'love':

--- code ---
---
language: html filename: index.html line_numbers: true line_number_start: 39
line_highlights: 42
---   
      <!-- The first drawing and instructions go here -->     
      <section> 

![The love facial expression.](love.png)

To make your anime character look like they are in **love**, replace the eyes with two rounded hearts. Remember to add highlight to the corners to create a better effect.</section>

--- /code ---

--- /task ---

--- task ---

**Test:** The instructions appear below your image and the word **love** is in bold. 

<iframe src="https://trinket.io/embed/html/893f1c44ad?outputOnly=true" width="350" height="700" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

--- /task ---

