# Elementos com flexbox em CSS

## Conceitos

- **Display: flex;** Torna uma tag em um elemento do tipo **flex container**, fazendo com que o seu filhos tornam-se em **flex itens**, pode ser aplicado em todo tipo de tag html (header, div, section, article, a, etc).

inserir uma imagem de container aqui

- **Flex direction;** O comportamento padrão de um flex container é horizontalmente, e também temos mais um direcionamento que é o **column**: que é o comportamento na vertical. Quando falamos de flex direction, estamos falando do eixo principal do container, definindo então a direção dos flex-items. Podemos modificar esses dois comportamentos em quatro orientações: **row** (padrão) - que é da esquerda para a direita; **row-reverse** - sentido oposto do row, ou seja, da direita para a esquerda; **column** - ordenação dos items de cima para baixo, na vertical; **column-reverse** - sentido oposto ao column, ou seja, de baixo para cima.

- **flex wrap;** aqui nos deparamos como uma solução para o nosso problema em container, qual problema seria esse? Uma vez que nos temos mais itens que o nosso container possa suportar, os itens começaram a vazar para fora do container, e uma solução para isso é o wrap, por padrão os container vem sem a quebra de linha "nowrap"(padrão). Com o flex-wrap, nos determinaremos se os itens irão quebrar ou não uma linha, ou até mesmo, fazer o reverso, quebrar uma linha e jogar o conteúdo da linha atual para baixo e mantém a nova linha sempre acima.
