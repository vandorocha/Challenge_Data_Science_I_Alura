# Challenge_Data_Science_I_Alura

Este repositório contém a solução para o desafio de **Data Science** proposto pela **Alura**, onde o objetivo é analisar os dados de vendas de quatro lojas fictícias da rede **Alura Store**. O principal desafio é recomendar qual loja deve ser fechada com base em análises de **faturamento**, **quantidade de vendas por categoria**, **avaliações de compras**, e outros indicadores de desempenho.

## Objetivo do Desafio

O objetivo deste projeto é identificar a loja menos eficiente entre quatro opções, com base em dados de vendas e desempenho. A partir da análise de variáveis como **faturamento**, **quantidade de vendas por categoria**, **avaliação média por loja** e **avaliação média por categoria**, buscamos uma justificativa sólida para a recomendação de fechamento.

## Estrutura do Projeto

Este projeto está estruturado da seguinte forma:

- **Análise de Faturamento**: Cálculo e comparação do faturamento total de cada loja.
- **Quantidade de Vendas por Categoria**: Identificação das categorias de produtos com maior número de vendas.
- **Avaliação Média por Loja**: Cálculo da média das avaliações dos clientes para cada loja.
- **Avaliação Média por Categoria**: Cálculo da média das avaliações dos clientes para cada categoria de produto.
- **Recomendação**: Com base nos dados, é feita uma recomendação sobre qual loja deve ser fechada.

## Resultados Obtidos

### 1. Faturamento Total por Loja

| Loja   | Faturamento     |
|--------|-----------------|
| Loja 1 | R$ 1.534.509,12 |
| Loja 2 | R$ 1.488.459,06 |
| Loja 3 | R$ 1.464.025,03 |
| Loja 4 | R$ 1.384.497,58 |

**Conclusão**: A **Loja 4** apresenta o menor faturamento, o que já sugere que ela está performando abaixo das demais.

### 2. Quantidade de Vendas por Categoria

| Categoria          | Quantidade de Vendas |
|--------------------|-----------------------|
| Móveis             | 1.886                 |
| Eletrônicos        | 1.772                 |
| Brinquedos         | 1.290                 |
| Eletrodomésticos   | 1.149                 |

**Conclusão**: As categorias **móveis** e **eletrônicos** são as mais vendidas, o que reflete em um maior faturamento para as lojas que focam nestes produtos.

### 3. Avaliação Média por Loja

| Local da Compra | Avaliação Média |
|-----------------|-----------------|
| Loja RN         | 4.21            |
| Loja SP         | 4.11            |
| Loja MT         | 4.11            |
| Loja MS         | 4.10            |

**Conclusão**: A **Loja RN** tem a maior avaliação média, enquanto a **Loja RR** apresenta a menor avaliação, sugerindo que ela tem a pior experiência de compra.

### 4. Avaliação Média por Categoria

| Categoria do Produto | Avaliação Média |
|----------------------|-----------------|
| Brinquedos           | 4.07            |
| Móveis               | 4.03            |
| Eletrodomésticos     | 4.01            |
| Livros               | 4.00            |

**Conclusão**: A categoria de **brinquedos** apresenta a melhor avaliação média.

### 5. Conclusão

Com base nas análises realizadas, a **Loja 4** é a mais ineficiente em termos de **faturamento**, **avaliação** e **quantidade de vendas por categoria**. Portanto, a recomendação é **fechar a Loja 4**.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação utilizada para análise dos dados.
- **Pandas**: Biblioteca para manipulação de dados.
- **Matplotlib**: Biblioteca para visualização de gráficos.
- **Jupyter Notebook**: Ambiente utilizado para a execução do código e documentação.

---

**Autor**: Vanderlândio Zeferino da Rocha
