# Jogo da Memória em Vanilla JavaScript

## Introdução de conceitos básicos de HTML5, CSS3 e JavaScript puro.

Projeto desenvolvido para a capacitação de JavaScript.

O jogo possui doze cartas e cada uma delas consiste em uma div pai chamada `.memory-card`, que possui dois elementos filhos img. O primeiro, chamado front-face, representa a face da carta e o segundo, back-face, o seu verso.
As cartas serão ainda envolvidas por um elemento section chamado `memory-game`.
Para que a carta vire ao ser clicada, deve ser adicionada uma classe ao elemento. Selecionando todos os elementos é possível iterar por um array de elementos adicionando um detector de eventos. Toda vez que uma carta for clicada uma função deverá ser chamada. A função deve acessar o array de classes e realizar a lógica necessária para virar a card.

Demonstração:
![Memory Game](./memory-game.gif)

## Especificações

* Ao clicar em uma carta ela deverá ser virada
* Uma carta virada não poderá ser clicada novamente para desvirar
* Não é possível virar mais de duas cartas ao mesmo tempo (exceto os pares já formados)
* Ao virar duas cartas: se elas forem um par deverão continuar viradas, caso contrário deverão desvirar após 2s
* Cartas com pares já formados não poderão ser desviradas
* Quando todas os pares forem virados:
  * Algum tipo de resposta, a critério do desenvolvedor, deverá ser mostrada ao jogador (um alert, uma nova página, etc), juntamente com a sua pontuação, definida por menor tempo ou menor quantidade total de giros 
  * Após a confirmação da vitória as cartas deverão ser reembaralhadas para jogar novamente
  * OPCIONAL: implementar um leaderboard com o nome dos jogadores
* Sinta-se livre para alterar o que achar conveniente, mas explique a intenção

## Conceitos importantes:

* selecionar elementos no DOM com `querySelector`
* iterar arrays com `forEach`
* adicionar/remover classes de elemento
* adicionar/remover ouvintes de eventos
* timeout (temporizador)
* HTML5: data-attribute (atributo de dados)
* CSS3: posicionamento, `flexbox`, transições

## Material para consulta e estudo

💙 [Playlist JavaScript, HTML e CSS](https://youtube.com/playlist?list=PLPjSrtKJfMyfDem5WcuE0_njkILHFXCpH)

💚 [Exercícios de JS](https://exercism.org/tracks/javascript/exercises)

Caso necessário também consulte o material disponível na capacitação de HTML/CSS ou no card de estudos no Trello

## Observação importante

Esse projeto não foi desenvolvido pela equipe do Ex Machina e se trata de uma adaptação de outra desenvolvedora (de fácil acesso). Solicitamos que não copiem o código e que realmente tentem fazer, para terem um melhor aprendizado. Caso tenha dificuldade entre em contato <3

