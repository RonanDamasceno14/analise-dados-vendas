# Análise de Dados de Vendas

Projeto de análise exploratória de dados desenvolvido em Python com o objetivo de praticar manipulação, agrupamento, análise e visualização de dados de vendas.

A análise utiliza uma base contendo informações sobre pedidos, produtos, clientes, categorias, regiões, vendas, descontos e lucros.

## Objetivo

Explorar os dados de vendas e identificar informações relevantes a partir da base, como:

- desempenho de vendas por categoria;
- distribuição das vendas por região;
- comportamento das vendas ao longo dos meses;
- identificação das categorias, regiões e períodos com maior volume de vendas.

## Tecnologias Utilizadas

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Análises Realizadas

### Vendas por Categoria

Os dados são agrupados por categoria para comparar o volume total de vendas entre:

- Technology
- Furniture
- Office Supplies

### Vendas por Região

A análise compara o total de vendas entre as regiões:

- West
- East
- Central
- South

### Vendas por Mês

As datas dos pedidos são convertidas para o formato de data e utilizadas para analisar a distribuição das vendas ao longo dos meses.

## Visualizações

O projeto utiliza Matplotlib para gerar visualizações que facilitam a interpretação dos resultados, incluindo:

- gráfico de vendas por categoria;
- gráfico de vendas por região;
- evolução das vendas por mês.

## Estrutura do Projeto

```text
analise-dados-vendas/
├── analise_vendas.ipynb
├── vendas.csv
└── README.md
```

## Como Executar

1. Clone este repositório.
2. Certifique-se de ter Python instalado.
3. Instale as bibliotecas necessárias:

```bash
pip install pandas matplotlib jupyter
```

4. Abra o Jupyter Notebook:

```bash
jupyter notebook
```

5. Execute as células do notebook em sequência.

## Aprendizados

Este projeto foi desenvolvido como prática de análise de dados com Python, trabalhando conceitos como:

- leitura de arquivos CSV;
- exploração de conjuntos de dados;
- agrupamento de informações com Pandas;
- manipulação de datas;
- análise de vendas;
- criação de gráficos com Matplotlib;
- interpretação de resultados.

## Autor

**Ronan Damasceno**

Estudante de Engenharia de Software.
