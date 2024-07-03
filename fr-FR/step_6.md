## Couleurs et polices

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

Dans cette étape, tu peux essayer différentes palettes de couleurs et choix de polices.

</div>
<div>
<iframe src="https://editor.raspberrypi.org/fr-FR/embed/viewer/anime-expressions-step-6" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

Maintenant que tu as commencé à ajouter des classes personnalisées à ton code, tu as peut-être remarqué que la couleur a été ajoutée à la page. En CSS, tu peux utiliser des **variables** pour créer une palette de couleurs pour ta page web.

Les variables CSS commencent par deux tirets : `--primary`.

Les couleurs sont spécifiées en utilisant la notation hexadécimale (hex) et commencent par '#'. Il existe de nombreux sites web sur lesquels tu peux trouver des couleurs hexadécimales à utiliser.

--- task ---

Va dans ton fichier `candy.css`. Ce fichier définit les variables de couleur pour la palette de couleurs candy.

Dans la palette de couleurs candy, la variable `--primary` est définie sur `#ebeaeb`, un gris pâle.

--- code ---
---
language: CSS
filename: candy.css
line_numbers: true
line_number_start: 1
line_highlights: 4
---
/* Palette de couleurs et polices Candy */

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

**Astuce :** CSS utilise différents marqueurs de commentaires en HTML. Les commentaires multilignes commencent par `/*` et se terminent par `*/`. Le navigateur ignore le code qui se trouve à l'intérieur des marqueurs de commentaires.

`/* Palette de couleurs Candy et polices */` est un exemple de commentaire CSS.

--- /task ---

Tu peux également utiliser des variables pour les polices. Le `--header-font` est défini sur `3rem 'Fredoka One', cursive;`

« 3rem » signifie que cette police doit être trois fois la taille de police normale.

« Fredoka One », cursive signifie que le navigateur doit utiliser la police « Fredoka One » s'il le peut. Si cette police n'est pas disponible, le navigateur devrait utiliser la **police de remplacement**, qui est `cursive`.

[[[web-fonts]]]

--- task ---

**Trouve** les variables qui définissent les polices de ta page web.

--- code ---
---
language: CSS
filename: candy.css
line_numbers: true
line_number_start: 15
line_highlights: 15-18
---

  --body-font: 1rem 'Verdana', sans-serif;
  --header-font: 3rem 'Fredoka One', cursive;
  --title-font: 2rem 'Fredoka One', cursive;
  --quote-font: lighter 1.5rem 'Chewy', cursive;
}

--- /code ---

--- /task ---

Les couleurs `primary` sont conçues pour être les plus utilisées dans le contenu principal de la page, suivies par les couleurs `secondary` puis `tertiary`. Cela signifie que tu peux facilement concevoir de nouvelles palettes de couleurs et basculer entre elles.

Le projet de démarrage comprend également un fichier de palette de couleurs vives appelé 'vivid.css'.

--- task ---

**Trouve** le fichier `vivid.css`.

Note que les variables de couleur et de police ont les mêmes noms que dans le fichier `candy.css`, mais les couleurs et polices utilisées sont différentes dans cette palette de couleurs.

--- code ---
---
language: CSS
filename: vivid.css
line_numbers: true
line_number_start: 1
---

/* Palette de couleurs vives et polices */

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

Va sur `index.html` et change le code de lien CSS pour le lien vers le fichier `vivid.css` :

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 21
line_highlights: 24
---   
    <!-- Inclure le fichier de style CSS -->

    <link href="style.css" rel="stylesheet" type="text/css" />
    <link href="vivid.css" rel="stylesheet" type="text/css" />

--- /code ---

--- /task ---

--- task ---

**Test :** clique sur le bouton **Run**.

Assure-toi que ta page web utilise désormais des couleurs plus vives et des polices différentes, telles que définies dans le fichier 'vivid.css'.

<iframe src="https://editor.raspberrypi.org/fr-FR/embed/viewer/anime-expressions-step-6" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>

--- /task ---
