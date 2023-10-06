# Dashboard de dados financeiros 💵
![Imagem de dados financeiros do unsplash](https://unsplash.com/pt-br/fotografias/qwtCeJ5cLYs)

Este repositório se trata de um dashboard de dados financeiros desenvolvido no Power BI, durante a realização do bootcamp "Ciência de dados com Python" do Santander, oferecido pela DIO.

## 🎯 Objetivo do projeto

O intuito do projeto foi realizar um dashboard de dados financeiros, através de dois relatórios: o primeiro com o foco em vendas, e o segundo no lucro.

## 💻 Fonte de dados 

Os dados foram extraídos de um conjunto de dados oferecido pelo próprio Power BI, que possui como título "financials". Trata-se de um conjunto de dados financeiros, que possui 700 linhas e 17 colunas, cuja variáveis encontram-se descritas no dicionário de dados abaixo.

#### 📖 Dicionário de dados

| Variável | Significado |
|----------|-------------|
| Segment | Segmento (governo, parceiros de canal, empresa, médio porte, pequenos negócios) |
| Country | País |
| Product | Produto |
| Discount Band | Faixa de desconto (nenhuma, baixa, média ou alta) |
| Units Sold | Unidades vendidas (quantidade) |
| Manufacturing Price | Preço de manufatura do produto |
| Sale Price | Preço de venda do produto |
| Gross Sales | Vendas brutas (quantidade) |
| Discounts | Valor do desconto fornecido no produto |
| Sales | Valor das vendas |
| COGS (Cost of Goods Sold) | Custo dos produtos vendidos |
| Profit | Valor do lucro ou prejuízo |
| Date | Data da venda |
| Month number | Número do mês da venda |
| Month name | Nome do mês da venda | 
| Year | Ano da venda |

## 📝 Sobre o projeto

Este projeto foi inteiramente realizado utilizando-se Microsoft Power BI. O dashboard encontra-se disponível neste repositório com o título "Dashboard_financials".

O dashboard conta com duas páginas, a primeira referente ao relatório de vendas, e a segunda ao relatório de lucro. É possível navegar pelas páginas através do botão no rodapé esquerdo (para utilizar botões no relatório é necessário apertar a tecla "control" + botão.). Ambos os relatórios contam com filtro de data. 

* **Relatório de vendas**

O relatório de vendas conta com cards com os alguns "big numbers", e vários gráficos. É possível realizar consultas à este relatório e depois utilizar a borracha no canto superior direito para voltar ao estado original do relatório. 
Há dois gráficos neste relatório que possuem dois tipos de visualizações: o gráfico de vendas por segmento, e o de vendas por país. O primeiro possui visualização em gráfico em barras e do tipo "donut". Já o de vendas por país possui visualização em forma de mapa e do tipo "treemap". Existem dois botões em cima de cada gráfico que possibilitam alternar entre as visualizações.
Além disto, este relatório apresenta o gráfico da distribuição de vendas ao longo do tempo por mês, onde se observa um pico no mês de outubro.

* **Relatório de lucro**

Este relatório conta com três tipos de gráfico: árvore hierárquica, treemap e gráfico em cascata. No gráfico de árvore hierárquica observa-se a distribuição do lucro por ano, e depois por país. Nos outros gráficos observa-se a divisão do lucro por segmento e por trimestre. respectivamente.


## 📈 Resultados

De acordo com os relatórios produzidos, foi possível chegar às seguintes conclusões:

* O valor total de vendas realizadas foi no valor de 118,73 milhões de dólares e 1,13 milhão de unidades foram vendidas, gerando um lucro de 16,89 milhões de dólares. Ao se observar o perfil das vendas, nota-se um destaque para o mês de outubro, que obteve um valor superior ha 21 milhões em vendas. Em contrapartida, o mês de março obteve o pior resultado, com 5,6 milhões em vendas.
* Em relação ao segmento, a maior fatia de vendas foi a do governo, que representou 44,22% do total de vendas. O mesmo se observou para o lucro, em que o governo se sobressaiu em relação aos outros segmentos, com um valor de 11,39 milhões de dólares.
* Os maiores países consumidores foram Estados Unidos, Canadá, França e Alemanha, respectivamente.
* O trimestre que apresentou mais lucro foi o quatro trimestre, totalizando 7,5 mihões de dólares.

