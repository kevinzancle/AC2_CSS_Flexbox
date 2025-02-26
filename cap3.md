# 3 Propriedades do Contêiner Flexível

## 3.1 flex-direction – Direção dos elementos

O flex direction altera a direção dos elementos como o dev quiser. Pode-se organizar os itens em colunas, linhas, inverter os itens e etc.

| Exemplo de comando  | Função  |
| :---- | :---- |
| flex-direction: row; | Organiza os itens em linha  |
| flex-direction: row-reverse; | Organiza os itens em linha reversa |
| flex-direction: collumn; | Organiza os itens de maneira colunar |
| flex-direction: collumn-reverse; | Organiza os itens de maneira colunar reversa |

## 3.2 flex-wrap – Quebra de linha dos itens

Define se os itens flexíveis são forçados a ficarem na mesma linha ou se podem ser quebrados em várias linhas. Se o argumento for válido, ele define a direção em que as linhas são empilhadas.

| Exemplo de comando  | Função  |
| :---- | :---- |
| flex: nowrap; | Itens são obrigados a permanecer na linha |
| flex: wrap; | Itens podem quebrar linha se não houver mais espaço |
| flex: wrap reverse; | Itens quebram a linha para cima (oposto do wrap) |

## 3.3 flex-flow – Atalho para flex-direction e flex-wrap

O flex-flow é a junção do flex-direction e do flex-wrap, onde as duas propriedades podem ser definidas em apenas uma linha, juntamente.

## 3.4 justify-content – Alinhamento horizontal dos itens

A propriedade define como o navegador distribui o espaço entre e em torno de itens de conteúdo ao longo do eixo X, sendo geralmente utilizado para alinhar itens horizontalmente.

| Exemplo de comando  | Função  |
| :---- | :---- |
| justify-content: start; | Alinha no começo do eixo X |
| justify-content: center; | Alinha no centro do eixo X |
| justify-content: space-between; | Espaça os elementos igualmente |
| justify-content: space-around; | Espaça igualmente os elementos com metade do espaçamento interno na parte externa |
| justify-content: space-evenly; | Espaça igualmente internamente e externamente |

## 3.5 align-items – Alinhamento vertical dos itens

Ele controla o alinhamento de itens no eixo Y, sendo utilizado para organizar os itens da maneira que for necessário.

| Exemplo de comando  | Função  |
| :---- | :---- |
| align-items: stretch; | Se os itens forem menores do que a caixa pai de alinhamento, os itens de tamanho automático serão igualmente ampliados para encher a caixa pai |
| align-items: center; | As caixas de margem dos itens flexíveis estão centradas dentro da linha no eixo cruzado |
| align-items: start; | Os itens são embalados um para o outro em direção à borda inicial. |
| align-items: end; | Os itens são embalados um para o outro em direção à borda final. |

## 3.6 align-content – Alinhamento em múltiplas linhas

A propriedade define a distribuição de espaço entre e em torno de itens de conteúdo ao longo de um eixo de cruzamento de flexbox. É a junção do justify-content e do align-items

![Descrição da imagem](https://css-tricks.com/wp-content/uploads/2018/10/align-content.svg)

[Capítulo 4](https://github.com/kevinzancle/AC2_CSS_Flexbox/blob/main/cap4.md)
