## Style your page

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

You have used HTML to add tags to your webpage. Now it is time to use CSS to add styles to your page. By the end of this step, your webpage will have different colours, fonts, and layout. 

</div>
<div>
<iframe src="https://trinket.io/embed/html/931f275be7?outputOnly=true" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>
</div>

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Cascading Style Sheets (CSS)**</span> is the language that you use to tell the web browser exactly how your webpage should look, including the positioning, colours, and fonts. We call this the style.
</p>

Every **rule** in CSS is made up of two parts: the **selector** and the **declaration**.

The **selector** is the part of HTML that you want to style. In this example it is `h1`. 

<div style="background-color:#2d2d2d; padding: 1em;">
  <pre><span style="color:#000; background-color:#d2d2d2; font-family:Consolas; font-size: 1em"> h1 </span
  ><span style=" color:#ccc;  font-family: Consolas, Monaco, 'Andale Mono', 'Ubuntu Mono', monospace; font-size: 1em">{
    color: blue;
    font-size: 12px;
  }</span></pre>
</div>
<br/>

The **declaration** is in curly brackets `{}`, it gives instructions of the styles that should be used. 

<div style="background-color:#2d2d2d; padding: 1em;">
<pre><span style="color:#ccc; font-family: Consolas, Monaco, 'Andale Mono', 'Ubuntu Mono', monospace; font-size: 1em"> h1 </span
><span style=" color:#000; background-color:#d2d2d2; font-family: Consolas; font-size: 1em"> { 
  color: blue; 
  font-size: 12px; 
 } </span></pre>
</div>
<br/>

### Linking the CSS file

The starter project includes CSS files which contains a set of useful rules. 

--- task ---

Unfold the `<head>` section of your code so that you can view the code inside it.

![A short animation demonstrating the mouse clicking on the little triangle next to the line 3 number to collapse the head code.](images/collapse.gif)

--- /task ---

--- task ---

At the bottom of your `<head></head>` section, there are links to two CSS style sheets that are currently commented out so that they are ignored by the web browser. 

Remove the `<!--` and `-->` arrows from the start and end of both lines of link code:

**Before**

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 21
line_highlights: 23-24
---   
    <!-- Include CSS style file -->

    <!-- <link href="style.css" rel="stylesheet" type="text/css" /> -->
    <!-- <link href="candy.css" rel="stylesheet" type="text/css" /> -->
  </head>

--- /code ---

**After**

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 21
line_highlights: 23-24
---   
    <!-- Include CSS style file -->

    <link href="style.css" rel="stylesheet" type="text/css" />
    <link href="candy.css" rel="stylesheet" type="text/css" />
  </head>

--- /code ---
--- /task ---

--- task ---

**Test:** HTML elements have default browser styles that you will have seen as you have been writing your HTML code. 

Take a look at your webpage in the right hand pane. Note that the styles and layout of your output has now changed. 

**Tip:** When you have seen the change you can collapse the `<head>` section by clicking the arrow next to it. 

--- /task ---

--- task ---

Click on the `style.css` tab in Trinket to view the code in the CSS file. This CSS file contains all of the CSS for your project, you will find out about some key parts of it as you create your webpage.

When you add CSS styling to an **element** it will apply that styling to every single element on the page that has the same tag. 

**Find:** Scroll down and find the rule that controls the style of the `<h2>`. 

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 109
line_highlights: 109-113
---  

h2 {
  font: var(--title-font); /* Font style stored in the title-font variable */
  text-align: left; /* Align the text */
  padding: 1.5rem; /* Add some space all around the heading */
}

--- /code ---

This rule states which font should be used, how the text should be aligned and how much space should be around the header. 

--- /task ---

--- task ---

At the moment the `<h2>` heading is aligned to the left.

Change the `text-align` property of the h2 rule to `center`.

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 109
line_highlights: 111
---  

h2 {
  font: var(--title-font); /* Font style stored in the title-font variable */
  text-align: center; /* Align the text */
  padding: 1.5rem; /* Add some space all around the heading */
}

--- /code ---

--- /task ---

--- task ---

**Test:** Look at your web page and make sure the 'Facial expressions' text is centered. 

**Debug:** Check the spelling of the word `center` - HTML uses American English spelling. 

<iframe src="https://trinket.io/embed/html/931f275be7?outputOnly=true" width="350" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

--- /task ---

