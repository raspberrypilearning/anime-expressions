## Adicione uma expressão facial

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Nesta etapa, adicione o primeiro desenho e as instruções à sua página Web.
</div>
<div>
<iframe src="https://editor.raspberrypi.org/pt-BR/embed/viewer/anime-expressions-step-3" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

Primeiro, crie uma seção para cada expressão facial na página web.

--- task ---

Encontre o comentário `<!-- O primeiro desenho e instruções vão aqui -->`.

Adicione as tags `<section></section>` para seu primeiro desenho e conteúdo de instruções.

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
        <h2>Expressões faciais</h2>
        <p>Dê uma olhada nessas expressões faciais e tente usá-las nos seus desenhos.</p>
      </section>
       
      <!-- O primeiro desenho e as instruções vão aqui -->     
      <section>
          
      </section> 

--- /code ---

--- /task ---

Seu projeto inicial contém imagens a serem usadas neste projeto. Para incluir uma imagem em uma página Web, você precisa saber o nome do arquivo. Primeiro, adicione uma imagem chamada `love.png`.

--- task ---

Dentro da sua nova seção, adicione uma tag `<img>` para exibir uma imagem. O **atributo** `src` dá o nome da imagem.

A tag `<img>` não tem uma tag final.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---
      <!-- O primeiro desenho e as instruções vão aqui -->     
      <section>
        <img src="love.png">
      </section> 

--- /code ---

--- /task ---

--- task ---

**Teste:** Clique no botão **Run**.

A imagem `love.png` aparece na sua página Web.

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Texto alternativo (Alt)**</span> é uma descrição de uma imagem e é importante na criação de um site acessível para descrever imagens para pessoas que não conseguem vê-las. O texto não aparece na página Web, mas é lido em voz alta por leitores de tela.
</p>

--- task ---

Adicione o atributo `alt` para fornecer texto alternativo para pessoas que não conseguem visualizar a imagem.

Você pode copiar a descrição da sua imagem e colá-la em seu código: `Expressão facial de apaixonado.`

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---   
      <!-- O primeiro desenho e as instruções vão aqui -->     
      <section>
        <img src="love.png" alt="A expressão facial apaixonado.">
      </section> 

--- /code ---

--- /task ---

--- task ---

Adicione um parágrafo de texto nas tags `<p></p>` para descrever como desenhar a expressão facial do anime apaixonado.

Você pode copiar o parágrafo e colá-lo no seu código:
`<p>Para fazer seu personagem de anime parecer apaixonado, substitua os olhos por dois corações arredondados. Você pode adicionar mais três corações dentro para dar um efeito divertido.</p>`

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 42
---   
      <!-- O primeiro desenho e as instruções vão aqui -->     
      <section>
        <img src="love.png" alt="A expressão facial apaixonado.">
        <p>Para fazer com que seu personagem pareça que está apaixonado, substitua os olhos por dois corações. Para dar um efeito mais interessante você pode adicionar três ou mais corações.</p>
      </section> 

--- /code ---

--- /task ---

A tag `<strong>` deixa textos importantes **em negrito**.

--- task ---

Adicione as tags `<strong>` ao redor da palavra 'apaixonado':

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 42
---   
      <!-- O primeiro desenho e as instruções vão aqui -->     
      <section>
        <img src="love.png" alt="A expressão facial apaixonado.">
        <p>Para fazer com que seu personagem pareça que está <strong>apaixonado</strong>, substitua os olhos por dois corações. Para dar um efeito mais interessante você pode adicionar três ou mais corações.</p>
      </section> 

--- /code ---

--- /task ---

--- task ---

**Teste:** Clique no botão **Run**.

As instruções aparecem abaixo da sua imagem e a palavra **apaixonado** fica em negrito.

<iframe src="https://editor.raspberrypi.org/pt-BR/embed/viewer/anime-expressions-step-3" width="500" height="750" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
--- /task ---

