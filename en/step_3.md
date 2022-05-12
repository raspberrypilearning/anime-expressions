## Add a facial expression

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
The next part of your anime webpage is separated into three sections. Each section has an image and some text. If the webpage is displayed on a mobile phone then the image should appear on top and the text will appear underneath.

In this step you will add the first drawing and instruction to your web page.

</div>
<div>
<iframe src="https://trinket.io/embed/html/893f1c44ad?outputOnly=true" width="350" height="250" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
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

--- task ---

image

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Alternative (Alt) text**</span> is a description . 
</p>

--- task ---


--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Web pages can be viewed on many different devices and should be <span style="color: #0faeb0">**responsive**</span> to each device. This means that if a user views your site on a mobile phone, it should respond to a smaller screen and if they view it on a desktop PC it should respond to a larger screen. 
</p>

--- task ---
**Test:** Drag the bar between the text editor and your web page and make the web page narrower. 

The text should move below the image. This is the layout that users with a mobile phone in portrait mode will see. 

Drag the bar back after testing so you can see the image and text side-by side. 

--- /task ---

--- save ---