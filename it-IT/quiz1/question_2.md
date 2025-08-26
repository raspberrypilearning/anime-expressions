--- question ---

---
legend: Domanda 2 di 3
---

Le classi CSS possono essere applicate al codice HTML per determinare come il contenuto dovrebbe apparire nel browser web.

Di seguito è riportato del codice CSS per stilizzare un sottotitolo. Quale riga di codice modificheresti per far visualizzare il sottotitolo sul lato destro?

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 1
line_highlights: 
---  

h2 {
    font: var(--title-font); 
    text-align: left; 
    padding: 1.5rem; 
}

--- /code ---

--- choices ---

- ( ) 1

  --- feedback ---

Prova a rivedere. La prima riga dice che il **selettore** a cui si applica la regola è il tag `h2`.

--- /feedback ---

- ( ) 2

  --- feedback ---

Non proprio. La seconda riga dice che il font per gli elementi con il tag `h2` è fornito dalla **variabile** `--title-font`.

--- /feedback ---

- (x) 3

  --- feedback ---

  Corretto! La terza riga ti permette di modificare l'allineamento del testo. Sostituendo `left` con `right`, il testo si allineerebbe sul lato destro.

  --- /feedback ---

- ( ) 4

  --- feedback ---

  Riprova. La quarta riga ti permette di regolare lo spazio attorno al sottotitolo.

  --- /feedback ---

--- /choices ---

--- /question ---
