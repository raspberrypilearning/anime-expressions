## Estilize com classes

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

Este passo te mostra como adicionar classes para personalizar os estilos na sua página.

</div>
<div>
<iframe src="https://editor.raspberrypi.org/pt-BR/embed/viewer/anime-expressions-step-5" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

Se você quiser aplicar estilo a elementos específicos, você pode criar uma **class** em um arquivo CSS. Você pode então adicionar um `class=` **attribute** a um elemento no seu código HTML para que o navegador saiba qual estilo deve ser aplicado.

O estilo da classe substitui qualquer estilo de elemento que já tenha sido aplicado. Observe que as alterações ocorrem à medida que você adiciona as classes ao seu código.

--- task ---

Seu arquivo CSS tem uma classe CSS personalizada chamada `border-bottom`. Essa classe adiciona uma borda de linha grossa e colorida no final de qualquer elemento HTML que a utiliza.

Vá até o arquivo `index.html` e encontre seu `header`.

Adicione `class="border-bottom"` após a palavra `header` na sua tag `header`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 27
line_highlights: 29
---
  <body>
    <!-- O código do cabeçalho da página vai aqui -->
    <header class="border-bottom">
      <h1>Desenhe um anime comigo</h1>
    </header>

--- /code ---

--- /task ---

--- task ---

Adicione a classe `border-top` ao seu código `footer` para aplicar uma borda grossa na parte superior do seu rodapé.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 55
line_highlights: 56
---
    <!-- Rodapé da página web -->
    <footer class="border-top">

--- /code ---

--- /task ---

A classe `primary` define uma cor de fundo e texto contrastante para a maior parte do conteúdo principal.

A classe `secondary` define uma combinação de cores adicional que fica bem com as cores da classe `primary`.

--- task ---

Adicione a classe `secondary` ao seu código `footer` para aplicar uma cor de fundo diferente ao seu rodapé.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 55
line_highlights: 56
---
    <!-- Rodapé da página web -->
    <footer class="border-top secondary">

--- /code ---

--- /task ---

--- task ---

Adicione `class="primary"` a `<main>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 34
---
    <!-- O conteúdo principal da página web fica entre as tags principais -->
    <main class="primary">

--- /code ---

--- /task ---

--- task ---

Adicione `secondary` ao `<header>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 28
line_highlights: 29
---
    <!-- O código do cabeçalho da página vai aqui -->
    <header class="border-bottom secondary">

--- /code ---

--- /task ---

A classe `tertiary` define uma combinação de cores adicional que fica bem com as cores das classes `primary` e `secondary`.

--- task ---

Adicione `class="tertiary"` ao **primeiro** elemento `<section>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 35
---
    <!-- O conteúdo principal da página web fica entre as tags principais -->
    <main class="primary">
      <section class="tertiary">
        <h2>Expressões faciais</h2>
        <p class="xcenter">Dê uma olhada nessas expressões faciais e tente usá-las nos seus desenhos.</p>
      </section>

--- /code ---

A classe `xcenter` no seu arquivo CSS alinha itens horizontalmente na página.

--- /task ---

--- task ---

Adicione `class="xcenter"` ao `<p>` na mesma seção.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 37
---
    <!-- O conteúdo principal da página web fica entre as tags principais -->
    <main class="primary">
      <section class="tertiary">
        <h2>Expressões faciais</h2>
        <p class="xcenter">Dê uma olhada nessas expressões faciais e tente usá-las nos seus desenhos.</p>
      </section>

--- /code ---

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
As páginas Web podem ser visualizadas em muitos dispositivos diferentes e devem ser <span style="color: #0faeb0">**responsivas**</span> para cada dispositivo. Isso significa que se um usuário visualizar sua página em um celular, ela deverá responder a uma tela menor, e se ele a visualizar em um PC de mesa, ela deverá responder a uma tela maior. 
</p>

CSS pode alterar o layout de uma página Web, além de ser usado para alterar cores, fontes e bordas.

--- task ---

Encontre o **segundo** `<section>`.

Adicione `class="wrap"` a tag `<section>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 40
---
    <!-- O primeiro desenho e as instruções vão aqui -->
    <section class="wrap">
      <img src="love.png" alt="A expressão facial apaixonado.">
      <p>Para fazer com que seu personagem pareça que está apaixonado, substitua os olhos por dois corações. Para dar um efeito mais interessante você pode adicionar três ou mais corações.</p>
    </section>

--- /code ---

--- /task ---

Você também pode adicionar bordas coloridas em diferentes estilos aos elementos HTML. A classe `dashed-border` no arquivo de estilo cria uma borda tracejada.

--- task ---

Adicione a classe `dashed-border` ao `<img>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---
    <!-- O primeiro desenho e as instruções vão aqui -->
    <section class="wrap">
      <img class="dashed-border" src="love.png" alt="A expressão facial apaixonado.">
      <p>Para fazer com que seu personagem pareça que está apaixonado, substitua os olhos por dois corações. Para dar um efeito mais interessante você pode adicionar três ou mais corações.</p>
    </section>

--- /code ---

--- /task ---

Você pode arredondar os cantos de um elemento com a classe `rounded`.

--- task ---

Adicione a classe `rounded` ao `<img>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---
    <!-- O primeiro desenho e as instruções vão aqui -->
    <section class="wrap">
      <img class="dashed-border rounded" src="love.png" alt="A expressão facial apaixonado.">
      <p>Para fazer com que seu personagem pareça que está apaixonado, substitua os olhos por dois corações. Para dar um efeito mais interessante você pode adicionar três ou mais corações.</p>
    </section>

--- /code ---
--- /task ---

--- task ---

**Teste:** Clique no botão **Run**.

Arraste a barra entre o editor de texto e sua página Web para torná-la mais estreita.

O texto deve se mover abaixo da imagem. Este é o layout para usuários que visualizam a página Web em um celular.

Arraste a barra de volta após testá-la, para você poder ver a imagem e o texto lado a lado.

![No Editor, o espaço vertical entre os dois painéis é arrastado da esquerda para a direita para mostrar que a página web se ajusta a telas menores.](images/drag-window.gif)

--- /task ---
