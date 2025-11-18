## Cores e fontes

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

Nesta etapa, você pode experimentar diferentes paletas de cores e opções de fontes.

</div>
<div>
<iframe src="https://editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-6" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

Agora que você começou a adicionar classes personalizadas ao seu código, você deve ter notado que cores foram adicionadas à página. Em CSS, você pode usar **variáveis** para criar uma paleta de cores para sua página web.

Variáveis CSS começam com dois traços: `--primary`.

As cores são especificadas usando notação hexadecimal (hex) e começam com '#'. Existem muitos sites onde você pode encontrar cores hexadecimais para usar.

\--- task ---

Vá para o seu arquivo `candy.css`. Este arquivo define as variáveis de cor para a paleta de cores suave.

Na paleta de cores doces, a variável `--primary` é definida como `#ebeaeb`, um cinza-claro.

## --- code ---

language: CSS
filename: candy.css
line_numbers: true
line_number_start: 1
line_highlights: 4
-------------------------------------------------------

/\* Paleta de cores tons pastéis e fontes \*/

:root {
\--primary: #ebeaeb;
\--onprimary: #625d61;
\--secondary: #f5bdd5;
\--onsecondary: #1d3d58;
\--tertiary: #b5a9b2;
\--ontertiary: #422215;
\--page: #ffffff;
\--onpage: #000000;
\--detail: #e697b9;
\--detail2: #415a89;

\--- /code ---

**Dica:** CSS usa marcadores de comentários diferentes do HTML. Comentários multilinha começam com `/*` e terminam com `*/`. O navegador ignora o código que está nos marcadores de comentários.

`/* Paleta de cores tons pastéis e fontes */` é um exemplo de comentário CSS.

\--- /task ---

Você também pode usar variáveis para fontes. A `--header-font` está definida como `3rem 'Fredoka One', cursiva; `

`3rem` significa que esta fonte deve ser o triplo do tamanho da fonte normal.

`'Fredoka One', cursiva` significa que o navegador deve usar a fonte 'Fredoka One' se possível. Se esta fonte não estiver disponível, o navegador deverá usar a **fonte alternativa**, sendo `cursiva`.

[[[web-fonts]]]

\--- task ---

**Encontre** as variáveis que definem as fontes da sua página da web.

## --- code ---

language: CSS
filename: candy.css
line_numbers: true
line_number_start: 15
line_highlights: 15-18
-----------------------------------------------------------

\--body-font: 1rem 'Verdana', sans-serif;
\--header-font: 3rem 'Fredoka One', cursive;
\--title-font: 2rem 'Fredoka One', cursive;
\--quote-font: lighter 1.5rem 'Chewy', cursive;
}

\--- /code ---

\--- /task ---

As cores `primárias` são projetadas para serem usadas principalmente no conteúdo principal da página, seguidas pelas `secundárias` e depois pelas cores `terciárias`. Isso significa que você pode facilmente criar paletas de cores e alternar entre elas.

O projeto inicial também inclui um arquivo de paleta de cores vivas nomeada `vivid.css`.

\--- task ---

**Encontre** o arquivo `vivid.css`.

Observe que as variáveis de cor e fonte têm os mesmos nomes do arquivo `candy.css`, mas as cores e fontes usadas diferem nesta paleta de cores.

## --- code ---

language: CSS
filename: vivid.css
line_numbers: true
line_number_start: 1
------------------------------------------------------------------------------

/\* Paleta de cores vivas e fontes \*/

:root {
\--primary: #68bbe5;
\--onprimary: #000000;
\--secondary: #e2008a;
\--onsecondary: #000000;
\--tertiary: #fdf100;
\--ontertiary: #000000;
\--page: #ffffff;
\--onpage: #000000;
\--detail: #ffa71a;
\--detail2: #41063c;

\--body-font: 1rem Verdana, sans-serif;
\--header-font: lighter 3rem "Bangers", cursive;
\--title-font: lighter 2rem "Bangers", cursive;
\--quote-font: lighter 1.5rem 'Chewy', cursive;
}

\--- /code ---

\--- /task ---

\--- task ---

Vá para `index.html` e altere o código do link CSS para vincular ao arquivo `vivid.css`:

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 21
line_highlights: 24
--------------------------------------------------------

```
<!-- Include CSS style file -->

<link href="style.css" rel="stylesheet" type="text/css" />
<link href="vivid.css" rel="stylesheet" type="text/css" />
```

\--- /code ---

\--- /task ---

\--- task ---

**Teste:** Clique no botão **Run**.

Certifique-se de que sua página web agora usa cores mais brilhantes e fontes diferentes, conforme definido no arquivo `vivid.css`.

<iframe src="https://editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-6" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>

\--- /task ---
