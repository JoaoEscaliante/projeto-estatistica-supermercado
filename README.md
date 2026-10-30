# Projeto 3 - Estatística descritiva e visualização de dados (Supermercado)

Análise de uma base de produtos de um supermercado do Chile, aplicando estatística
descritiva (média, mediana, desvio padrão, outliers) e visualização de dados em Python.

## O que foi feito
- Média e mediana do preço normal por categoria
- Desvio padrão por categoria e identificação da categoria com maior dispersão (lacteos)
- Boxplot de lacteos e identificação de outliers (43 de 447 produtos)
- Gráfico de barras com a média de desconto por categoria
- Treemap interativo por categoria e marca com a média de desconto

## Principais conclusões
- Em 6 das 7 categorias a média de preço é maior que a mediana, indicando poucos
  produtos muito caros puxando a média para cima.
- Lacteos tem o maior desvio padrão, e seus outliers são principalmente packs de 12 litros de leite.
- Congelados e cuidado pessoal têm as maiores médias de desconto, e cerca de 89% dos
  produtos da base não têm desconto.

## Arquivos
- `Projeto_M13_resolvido.ipynb`: código completo e análises
- `MODULO7_PROJETOFINAL_BASE_SUPERMERCADO.csv`: base de dados
- `boxplot_lacteos.png`, `barras_desconto.png`: gráficos
- `mapa_interativo.html`: treemap interativo (baixe e abra no navegador)

## Como executar
1. Instale as bibliotecas: `pip install pandas matplotlib plotly`
2. Deixe o CSV na mesma pasta do notebook
3. Abra o notebook e execute as células em ordem

## Tecnologias
Python, Pandas, Matplotlib, Plotly
