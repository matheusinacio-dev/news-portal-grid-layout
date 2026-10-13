# Portal de notícias usando grid-layout

## Uso misto de grid-layout e flexbox para projetar um portal de notícias

Esse projeto foi construído como forma de fortalecer os aprendizados em CSS Grid e suas diferenças em relação ao o CSS Flexbox.

A ideia surgiu da trilha de estudo Full-Stack da Rocketseat seguindo um layout do Figma. E as decisões tomadas tentam aproximar o projeto da referência.

### Stack utilizada

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

### Preview

![Preview do projeto em GIF](assets/news-portal-grid-layout-otimizado.gif)

### Demo

[Ver projeto ao vivo](https://matheusinacio-dev.github.io/news-portal-grid-layout/)

### Limitações atuais

Pouca responsividade entre diferentes telas. <br>
O site foi projetado para computadores. Então, seu uso em tablets e celulares muitas vezes resulta em quebras de layout.
Uma possível solução seria usar @media queries para adaptar o layout a diferentes tamanhos de tela. Juntamente com unidades mais responsivas, como em e rem.

### Principais aprendizados

Foi esse projeto que me introduziu a utility-first classes no CSS. Então em utility.css, busquei criar classes:

- para propósitos únicos;
- nomeadas pelo que fazem;
- fáceis de reutilizar.

Também, aprendi sobre nesting CSS, em que escrevemos estilos dentro de estilos imitando um pouco a hierarquia do HTML. Muito útil para evitar criar muitos seletores, porém é pouco específico e se usado demais fica difícil de entender.

Num geral, usei os dois conceitos de modo equilibrado.
