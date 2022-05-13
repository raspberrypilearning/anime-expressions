## Add a facial expression

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In this step you will add the first drawing and instruction to your web page.
</div>
<div>
<iframe src="https://trinket.io/embed/html/893f1c44ad?outputOnly=true" width="370" height="700" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>
</div>

You will create a section for each facial expression on the webpage. 

--- task ---

Find the comment `<!-- The first drawing and instructions goes here -->`.

Add in the `<section></section>` tags for your first drawing and instruction content. 

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
        <h2>Facial expressions</h2>
        <p>Take a look at these facial expressions and try them in your own drawings.</p>
      </section>
       
      <!-- The first drawing and instructions goes here -->     
      <section>
          
      </section> 

--- /code ---

--- /task ---

Your starter project contains images to use in this project. To include an image on a web page you need to know the filename. First you will be adding an image called `love.png`.

--- task ---

Inside your new section, add an `<img>` tag to display an image. The `src` **attribute** gives the name of the image.

 The `<img>` tag doesn't have an end tag.
 
--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---
      <!-- The first drawing and instructions goes here -->     
      <section>
        <img src="love.png">
      </section> 

--- /code ---

--- /task ---

--- task ---

**Test:** The `love.png` image will appear on your webpage.

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Alternative (Alt) text**</span> is a description of an image and is important in accessible web design to describe images to people who are unable to see them. The text will not appear on the webpage but will be read aloud by screen readers.
</p>

--- task ---

Add the `alt` property to provide alternative text for people who cannot view the image. 

You can copy the description of your image and paste it into your code `The love facial expression.`

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---   
      <!-- The first drawing and instructions goes here -->     
      <section>
        <img src="love.png" alt="The love facial expression.">
      </section> 

--- /code ---

--- /task ---

--- task ---

Add a paragraph of text in `<p></p>` tags to describe how to draw the love anime facial expression. 

You can copy the paragraph and paste it into your code `To make your anime character look like they are in love, replace the eyes with two rounded hearts. Remember to add highlight to the corners to create a better effect.`

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---   
      <!-- The first drawing and instructions goes here -->     
      <section>
        <img src="love.png" alt="The love facial expression.">
        <p>To make your anime character look like they are in love, replace the eyes with two rounded hearts. Remember to add highlight to the corners to create a better effect.</p>
      </section> 

--- /code ---

--- /task ---

--- task ---

**Test:** The instructions will appear below your image. 

<iframe src="https://trinket.io/embed/html/893f1c44ad?outputOnly=true" width="350" height="700" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

--- /task ---

