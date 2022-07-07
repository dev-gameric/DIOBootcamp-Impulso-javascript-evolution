# Elementos com flexbox em CSS

## Conceitos

- **Display: flex;** Torna uma tag em um elemento do tipo **flex container**, fazendo com que o seu filhos tornam-se em **flex itens**, pode ser aplicado em todo tipo de tag html (header, div, section, article, a, etc).

inserir uma imagem de container aqui

- **Flex direction;** O comportamento padrão de um flex container é horizontalmente, e também temos mais um direcionamento que é o **column**: que é o comportamento na vertical. Quando falamos de flex direction, estamos falando do eixo principal do container, definindo então a direção dos flex-items. Podemos modificar esses dois comportamentos em quatro orientações: **row** (padrão) - que é da esquerda para a direita; **row-reverse** - sentido oposto do row, ou seja, da direita para a esquerda; **column** - ordenação dos items de cima para baixo, na vertical; **column-reverse** - sentido oposto ao column, ou seja, de baixo para cima.

- **flex wrap;** aqui nos deparamos como uma solução para o nosso problema em container, qual problema seria esse? Uma vez que nos temos mais itens que o nosso container possa suportar, os itens começaram a vazar para fora do container, e uma solução para isso é o wrap, por padrão os container vem sem a quebra de linha "nowrap"(padrão). Com o flex-wrap, nos determinaremos se os itens irão quebrar ou não uma linha, ou até mesmo, fazer o reverso, quebrar uma linha e jogar o conteúdo da linha atual para baixo e mantém a nova linha sempre acima.

- **flex flow;** o flex flow é como um atalho para o flex direction e o flex wrap que já vimos anteriomente nele você pode definir o flex direction e o flex wrap dentro dele, ele não é muito utilizado pelo fato de que quando mudamos o flex direction para column mantemos o padrão do flex wrap que relembrando, é o nowrap.

- **justify content;** O justify content será encarregado de alinha os itens filhos dentro de um container de acordo com a direção determinada e também o alinhamento entre os itens filhos entre ele, caso o item filho ocupe 100% do container, essa aplicação não fará sentido. O **flex-start** fará o alinhamento do início do container, ou seja, da esquerda para a direita, o **flex-end** fará o alinhamento do fim para o início do container, ou seja, da direita para a esquerda, o **center** ao centro do container, o **space-between** ele será responsável na parte de alinhamento, ou seja, determinar o espaçamento entre os elementos igualmente.
