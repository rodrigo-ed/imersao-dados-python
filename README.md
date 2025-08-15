# Dashboard de Salários na Área de Dados

Este projeto apresenta um dashboard interativo desenvolvido com [Streamlit](https://streamlit.io/) para análise de salários na área de dados, utilizando dados reais de profissionais de diversos cargos, senioridades, tipos de contrato e países.

## Funcionalidades

- Visualização de métricas principais (salário médio, máximo, total de registros, cargo mais frequente)
- Filtros por ano, senioridade, tipo de contrato e tamanho da empresa
- Gráficos interativos com Plotly:
  - Top 10 cargos por salário médio
  - Distribuição de salários anuais
  - Proporção dos tipos de trabalho (remoto/presencial)
  - Salário médio de Cientista de Dados por país
- Tabela detalhada dos dados filtrados

## Como executar

1. Instale as dependências:
   ```sh
   pip install -r requirements.txt
2. Execute o aplicativo:
   ```sh
   streamlit run app.py [você dever ter uma conta no Streamlit para executar]

## Estrutura do projeto

- app.py: Código principal do dashboard
- dados-imersao-final.csv: Base de dados utilizada
- requirements.txt: Dependências do projeto
