# Ibama - Análise de Autos de Infração

Este repositório contém o notebook **Ibama.ipynb**, que realiza análises exploratórias sobre autos de infração ambientais emitidos pelo IBAMA.  
O objetivo é organizar, limpar e visualizar os dados para apoiar estudos sobre desmatamento e fiscalização ambiental.

## Conteúdo
- **Importação de dados**: leitura de arquivos originais em formato CSV/GeoJSON.
- **Limpeza de dados**: tratamento de valores nulos, padronização de colunas e criação de variáveis derivadas (ex.: ano da infração).
- **Exploração temporal**: evolução dos autos de infração por ano.
- **Exploração espacial**: distribuição por estados e municípios.
- **Visualizações**: tabelas, gráficos e mapas temáticos.

## Requisitos
- Python 3.12+
- Bibliotecas:
  - pandas
  - geopandas
  - matplotlib
  - requests

Instale com:
```bash
pip install pandas geopandas matplotlib  requests
