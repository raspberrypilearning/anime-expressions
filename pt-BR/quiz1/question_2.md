\--- question ---

---

## legend: Pergunta 2 de 3

As classes CSS podem ser aplicadas ao código HTML para decidir como o conteúdo deve aparecer no navegador web.

Abaixo está um código CSS para estilizar um subtítulo. Qual linha de código você alteraria para que o subtítulo fosse exibido no lado direito?

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

Dê outra olhada. A primeira linha diz que o **seletor** ao qual a regra se aplica é a tag `h2`.

\--- /feedback ---

- ( ) 2

  \--- feedback ---

Quase. A segunda linha diz que a fonte para elementos com a tag `h2` é fornecida pela \*\*variável` --title-font`.

\--- /feedback ---

- (x) 3

  \--- feedback ---

  Correto! A terceira linha permite que você altere o alinhamento do texto. Ao alterar `esquerda` para `direita`, o texto seria alinhado no lado direito.

  \--- /feedback ---

- ( ) 4

  \--- feedback ---

  Tente novamente. A quarta linha permite ajustar o espaço ao redor do subtítulo.

  \--- /feedback ---

\--- /choices ---

\--- /question ---
