\--- question ---

---

## legend: Question 2 sur 3

Les classes CSS peuvent être appliquées au code HTML pour décider de la manière dont le contenu doit apparaître dans le navigateur web.

Tu trouveras ci-dessous du code CSS pour styliser un sous-titre. Quelle ligne de code modifierais-tu pour que le sous-titre s'affiche sur le côté droit ?

## --- code ---

language: css
filename: style.css
line_numbers: true
line_number_start: 1
line_highlights:
-----------------------------------------------------

h2 {
font: var(--title-font);
text-align: left;
padding: 1.5rem;
}

\--- /code ---

\--- choices ---

- ( ) 1

  \--- feedback ---

Regarde encore une fois. La première ligne indique que le **sélecteur** auquel la règle s'applique est la balise `h2`.

\--- /feedback ---

- ( ) 2

  \--- feedback ---

Pas tout à fait. La deuxième ligne indique que la police des éléments avec la balise `h2` est fournie par la **variable** `--title-font`.

\--- /feedback ---

- (x) 3

  \--- feedback ---

  Correct ! La troisième ligne te permet de modifier l'alignement du texte. En remplaçant `left` par `right`, le texte s'alignerait sur le côté droit.

  \--- /feedback ---

- ( ) 4

  \--- feedback ---

  Réessaie. La quatrième ligne permet d'ajuster l'espace autour du sous-titre.

  \--- /feedback ---

\--- /choices ---

\--- /question ---
