<div align="center">
<h1  align="center">Maratona Explorer</h1>
<h2>Rocketseat</h2>
<a><img  src="https://img.shields.io/badge/Boosting%20people-ROCKETSEAT-blueviolet"  alt="Badge Rocketseat"> </a>
</div>

<div  align="center"> <img  src="https://i.imgur.com/u2i5MAL.gif"  alt="Gif da Página"  width="680"> </div>

---
<p  align="center"> <a  href="https://opensource.org/licenses/MIT"> <img  src="https://img.shields.io/badge/License-MIT-blue.svg"  alt="License MIT"> </a></p>

--- 

## :bulb: Do que se trata o projeto

Landing Page contendo uma espécie de jogo de adivinhação onde o usuário insere uma pergunta e a página retorna uma resposta aleatória.

  

## :computer: Motivação

Evento promovido pela Rocketseat com uma semana de aulas para devs iniciantes saírem do zero, aprender fundamentos e construir um portifólio. Período do evento: de 05 a 13 de junho de 2022.

## :wrench: Alterações & Melhorias
Após reproduzir a landing page exatamente como foi desenvolvida na maratona resolvi fazer minhas estilizações para fins de treinamento. As mudanças foram as seguintes:
* Alteração do fundo para o `background-color: #1B0430`;
* Troca da `font-family` de sans-serif padrão para Amaranth;
* Alteração da cor da fonte de branco para `color: #1DD3B0`; 
* Troca da imagem principal da bola de cristal pelo png de um mago;
* Inserção de um segundo botão com a função de apagar a pergunta no input;
* Alterações diversas em tamanhos e proporções.

## :book: Aprendizado
É sempre importante aprofundar a bases de conhecimento por mais que pareça repetitivo pois cada abordagem é um aprendizado a mais. 

Nas alterações e melhorias feitas no projeto conheci a função de apagar o conteúdo de um campo (no caso o input com a pergunta). Por mais básica que seja essa melhoria ela deixou a página de fato mais funcional. Segue código da função:

```javascript
function  limparPergunta() {
inputPergunta.value =  "";
inputPergunta.focus();
}
```
Outro aprendizado foi com a estilização dos botões. Eu queria um efeito diferente então lembrei de um estilo que vi em algum perfil de "Dev Influencer" no Instagram. Trata-se de um botão com uma espécie de efeito analógico que consiste basicamente num box-shadow e em valores nos eixos X e Y no translate. Ficou da seguinte forma:

```css
button {
display:  inline-block;
width:  45%;
padding:  1rem;
font-size:  1.7rem;
border-radius:  8px;
border:  none;
background-color:  #1DD3B0;
box-shadow:  #1D23B0  4px  4px  0px;
color:  #1B0430;
transition: transform 200ms, box-shadow 200ms;
margin:  0.8rem;
}

button:active {
transform:  translateY(4px) translateX(4px);
box-shadow:  #1D23B0  0px  0px  0px;
}
```
Tenho plena consciência que poderia fazer um código mais limpo e funcional mas acredito que isso virá com o tempo. 
Continuarei me aperfeiçoando.
  

## :battery: Stack Utilizada

- ![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

- ![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

- ![Javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

  

## :memo: Licença

Este projeto está licenciado sob a Licença MIT - consulte a <a  href="https://opensource.org/licenses/MIT"  target="_blank">página de Licença</a>.
