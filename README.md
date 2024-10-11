# Relatório de Análise de Dados Automatizada

Este projeto tem como objetivo gerar um relatório de análise de dados utilizando Python, com visualizações gráficas e estatísticas descritivas. O relatório é gerado em formato HTML e é baseado em um template Jinja2.

## Integrantes
- Victor Kenzo Toma - RM
- Murilo Marsola Eloys - RM552117

## Estrutura do Projeto

- template.html: Template HTML utilizado para renderizar o relatório.
- notebook: Projeto com comandos de python salvo no notebook (Arquivo 'ipynb').
- report_jinja.html: Arquivo HTML gerado com os resultados da análise.

## Pré-requisitos

Para executar este projeto, você precisará ter instalado em seu ambiente:

- Python 3.x
- Bibliotecas:
  - pandas
  - matplotlib
  - seaborn
  - jinja2

## Como Usar
1. *Prepare seus dados*: Certifique-se de que seus dados estão em um DataFrame do Pandas chamado df.
2. *Execute o comando*: Execute o comando do notebook Python. Isso irá gerar um arquivo HTML chamado report_jinja.html.

## Detalhes da Análise
O código realiza as seguintes etapas:
- Calcula a quantidade de valores ausentes em cada coluna do DataFrame.
- Gera um gráfico de barras mostrando a quantidade de dados faltantes por coluna.
- Para cada coluna numérica, calcula as seguintes estatísticas:
  - Média
  - Mediana
  - Máximo
  - Mínimo
- Gera um relatório HTML que inclui os resultados da análise e suas visualizações.
