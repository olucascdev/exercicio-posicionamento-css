# exercicio-posicionamento-css
 Exercicio de posicionamento no css
 
grid-template-columns e grid-template-rows:

Essas propriedades definem o layout de colunas e linhas de uma grade CSS.
Com grid-template-columns, você especifica a largura das colunas da grade.
Com grid-template-rows, você especifica a altura das linhas da grade.
Você pode definir o tamanho das colunas e linhas usando valores fixos, valores relativos (porcentagens, fr, etc.) ou usando funções como repeat() e auto.

grid-column e grid-row:

Essas propriedades são usadas para colocar um item em uma grade CSS, especificando a coluna e a linha em que ele deve ser colocado.
grid-column define as colunas onde o item está localizado.
grid-row define as linhas onde o item está localizado.
Você pode especificar os números das colunas e linhas, ou usar valores como span para indicar quantas colunas ou linhas o item deve ocupar.

align-content e justify-content:

Essas propriedades são usadas para alinhar o conteúdo dentro de um contêiner de grade, tanto no eixo da linha quanto no eixo da coluna.
align-content controla o alinhamento vertical do conteúdo dentro do contêiner de grade.
justify-content controla o alinhamento horizontal do conteúdo dentro do contêiner de grade.
Você pode usar valores como flex-start, center, flex-end, space-between, space-around e space-evenly para especificar o alinhamento.

align-items e justify-items:

Essas propriedades são usadas para alinhar os itens individuais dentro das células da grade.
align-items controla o alinhamento vertical dos itens dentro das células da grade.
justify-items controla o alinhamento horizontal dos itens dentro das células da grade.
Estas propriedades funcionam de forma semelhante a align-content e justify-content, mas afetam os itens individualmente em vez de todo o conteúdo da grade.


align-self e justify-self:

Essas propriedades são usadas para anular o alinhamento padrão de um item dentro de uma grade.
align-self controla o alinhamento vertical de um item dentro de sua célula de grade.
justify-self controla o alinhamento horizontal de um item dentro de sua célula de grade.
Elas substituem os valores de alinhamento definidos pelos valores padrão de align-items e justify-items.
