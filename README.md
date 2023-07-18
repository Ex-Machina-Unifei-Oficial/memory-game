# Jogo da Memória em Vanilla JavaScript

## Introdução de conceitos básicos de HTML5, CSS3 e JavaScript puro.

O jogo possui doze cartas e cada uma delas consiste em uma div pai chamada `.memory-card`, que possui dois elementos filhos img. O primeiro, chamado front-face, representa a face da carta e o segundo, back-face, o seu verso.
As cartas serão ainda envolvidas por um elemento section chamado `memory-game`.
Para que a carta vire ao ser clicada, deve ser adicionada uma classe ao elemento. Selecionando todos os elementos é possível iterar por um array de elementos adicionando um detector de eventos. Toda vez que uma carta for clicada umaa função deverá ser chamada. A função deve acessar o array de classes e realizar a lógica necessária para virar a card.

Conceitos importantes:

* selecionar elementos no DOM com `querySelector`
* iterar arrays com `forEach`
* adicionar/remover classes de elemento
* adicionar/remover ouvintes de eventos
* timeout (temporizador)
* html5: data-attribute (atributo de dados)
* css3: posicionamento, `flexbox`, transições
---
💚 [Exercícios](https://exercism.org/tracks/javascript/exercises)
💙 [Playlist JavaScript, HTML e CSS](https://youtube.com/playlist?list=PLPjSrtKJfMyfDem5WcuE0_njkILHFXCpH)

---

![Memory Game](./memory-game.gif)
