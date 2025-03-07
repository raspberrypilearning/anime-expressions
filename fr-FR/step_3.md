## Ajouter une expression faciale

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Dans cette étape, ajoute le premier dessin et les instructions à ta page web.
</div>
<div>
<iframe src="https://editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-3" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

Tout d'abord, crée une section pour chaque expression faciale de la page web.

\--- task ---

Trouve le commentaire `<!-- Le premier dessin et les instructions vont ici -->`.

Ajoute les balises `<section></section>` pour ton premier contenu de dessin et d'instruction.

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 40-42
-----------------------------------------------------------

```
<main>
  <section>
    <h2>Facial expressions</h2>
    <p>Take a look at these facial expressions and try them in your own drawings.</p>
  </section>
   
  <!-- The first drawing and instructions go here -->     
  <section>
      
  </section> 
```

\--- /code ---

\--- /task ---

Ton projet de démarrage contient des images à utiliser dans ce projet. Pour inclure une image sur une page web, tu dois connaître le nom du fichier. Tout d’abord, ajoute une image appelée 'love.png'.

\--- task ---

Dans ta nouvelle section, ajoute une balise `<img>` pour afficher une image. L'**attribut** `src` donne le nom de l'image.

La balise `<img>` n'a pas de balise fermante.

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
--------------------------------------------------------

```
  <!-- The first drawing and instructions go here -->     
  <section>
    <img src="love.png">
  </section> 
```

\--- /code ---

\--- /task ---

\--- task ---

**Test :** clique sur le bouton **Run**.

L'image `love.png` apparaît sur ta page web.

\--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Le texte alternatif (Alt)**</span> est une description d'une image et est important dans la conception de sites web accessibles pour décrire les images aux personnes qui ne peuvent pas les voir. Le texte n'apparaît pas sur la page web mais il est lu à voix haute par les lecteurs d'écran.
</p>

\--- task ---

Ajoute l'attribut `alt` pour fournir un texte alternatif aux personnes qui ne peuvent pas voir l'image.

Tu peux copier la description de ton image et la coller dans ton code : 'L'expression faciale de l'amour.'

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
--------------------------------------------------------

```
  <!-- The first drawing and instructions go here -->     
  <section>
    <img src="love.png" alt="The love facial expression.">
  </section> 
```

\--- /code ---

\--- /task ---

\--- task ---

Ajoute un paragraphe de texte dans les balises `<p></p>` pour décrire comment dessiner l'expression faciale amour d'anime.

Tu peux copier le paragraphe et le coller dans ton code :
`<p>Pour que ton personnage d'anime ressemble à un personnage amoureux, remplace les yeux par deux cœurs arrondis. Tu peux ajouter trois cœurs supplémentaires à l'intérieur pour un effet amusant.</p>`

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 42
--------------------------------------------------------

```
  <!-- The first drawing and instructions go here -->     
  <section>
    <img src="love.png" alt="The love facial expression.">
    <p>To make your anime character look like they are in love, replace the eyes with two rounded hearts. You can add three more hearts inside for a fun effect.</p>
  </section> 
```

\--- /code ---

\--- /task ---

La balise `<strong>` met le texte important en **gras**.

\--- task ---

Ajoute des balises `<strong>` autour du mot 'amour' :

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 42
--------------------------------------------------------

```
  <!-- The first drawing and instructions go here -->     
  <section>
    <img src="love.png" alt="The love facial expression.">
    <p>To make your anime character look like they are in <strong>love</strong>, replace the eyes with two rounded hearts. You can add three more hearts inside for a fun effect.</p>
  </section> 
```

\--- /code ---

\--- /task ---

\--- task ---

**Test :** clique sur le bouton **Run**.

Les instructions apparaissent sous ton image et le mot **amour** est en gras.

<iframe src="https://editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-3" width="500" height="750" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
--- /task ---

