## Add a header and introduction

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In this step, you will add a header and an introduction to your anime webpage.
</div>
<div>
![A screenshot of the output of step 2. A webpage with a heading, subheading and introductory text.](images/step2-output.PNG){:width="300px"}
</div>
</div>

In HTML you can type words directly into the code and it will appear, unformatted, on the webpage.

--- task ---

**Try it:** Type some words into the left-hand side of the project below. The words you type will automatically appear on the webpage to the right. 

+ What happens if you type multiple lines of text? 
+ Would you like to view a webpage that looked like this? 

<iframe src="https://trinket.io/embed/html/d932ddf89f" width="100%" height="350" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

--- /task ---

--- task ---

Open the [starter project](https://trinket.io/html/2d58893157){:target="_blank"}.

--- /task ---

Typically, a webpage has three parts. A **header**, the **main** content and a **footer**. 

### Add a header 

The starter project already has `<header>` tags; everything you add here will appear in your webpage header. 

--- task ---

A tag lets the browser know what you would like to do with the content inside it. A `<h1>` tag is used to say that this content is the largest header on the page. 

On line 29, add in the `<h1></h1>` **tags**.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 26
line_highlights: 29
---
  <body>
    <!-- The page header code goes here -->
    
    <h1></h1>

--- /code ---

**TIP**: In HTML, you don’t need to add in the indents for the code to work. However, it is a good idea to indent the sections of your code to make them easier for you and others to read. 

--- /task ---

--- task ---

Add the text `Draw anime with me` between the two `<h1>` tags. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 26
line_highlights: 29
---
  <body>
    <!-- The page header code goes here -->
    
    <h1>Draw anime with me</h1>

--- /code ---

--- /task ---

You can now see that some styling has been applied to the text. It is bold and much larger than before. 

### The main content

--- task ---

You are now going to add a subheading in the **main** part of your webpage. Any main content should be placed between the `<main>` tags. 

Add the subheading tags `<h2>` to line 34.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 32
line_highlights: 34
---
     <main>
      
      <h2></h2>

--- /code ---

--- /task ---

--- task ---

Now enter the subheading text `Facial expressions` between the `<h2>` tags. Your code should look like this:

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 32
line_highlights: 34
---
     <main>
      
      <h2>Facial expressions</h2>

--- /code ---

Notice how the text is slightly smaller than the big heading above and has the bold styling. This is because `<h2> ` is a smaller heading than `<h1>`.

--- /task ---

--- task ---

You are now going to add a paragraph of text as an introduction to your anime webpage. 

Add the paragraph `<p>` tags to line 35. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 32
line_highlights: 35
---
   <main>
 
      <h2>Facial expressions</h2>     
      <p></p>

--- /code ---

--- /task ---

--- task ---

Between the `<p>` tags, you need to add in the introductory text. This is:

`Take a look at these facial expressions and try them in your own drawings.`

Your code should look like this:

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 32
line_highlights: 35
---
   <main>
  
      <h2>Facial expressions</h2>     
      <p>Take a look at these facial expressions and try them in your own drawings.</p>

--- /code ---

--- /task ---

You can now see that the text appears under the subheading and uses the default paragraph styling. 

Well done! Your page now has a header, subheading and an introductory paragraph. 

--- save ---

