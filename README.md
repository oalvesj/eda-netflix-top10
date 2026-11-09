# EDA — Netflix Daily Top 10

Análise exploratória de dados (EDA) da base **Netflix Daily Top 10**, feita em Python com Pandas e Matplotlib em um Jupyter Notebook. O objetivo é entender a base antes de qualquer modelagem: tipos de dados, período, tamanho, valores nulos e outliers.

## O que foi analisado

- Tipos de dados disponíveis
- Período da análise
- Tamanho da base de dados
- Verificação de dados nulos
- Outliers

## Principais achados

- A base tem **7.100 registros** e **10 colunas**, cobrindo o período de **01/04/2020 a 11/03/2022**.
- Os tipos incluem datas, rankings e pontuações (numéricos) e título/tipo (texto).
- Há valores nulos relevantes em `Netflix Exclusive`, `Last Week Rank` e `Year to Date Rank` (os rankings usam `-` como ausência de valor).
- As colunas `Days In Top 10` e `Viewership Score` apresentam muitos outliers superiores: títulos de grande sucesso que ficaram muito tempo no top 10.

## Tecnologias

- Python 3
- Pandas
- Matplotlib
- Jupyter Notebook

## Como rodar

1. Instale as dependências:

```bash
pip install pandas matplotlib jupyter ipykernel
```

2. Abra o notebook `eda.ipynb` (no VSCode, Jupyter ou JupyterLab), selecione o kernel Python e execute todas as células.

O arquivo `netflix_daily_top_10.csv` precisa estar na mesma pasta do notebook.

## Arquivos

- `eda.ipynb` — notebook com a análise completa
- `netflix_daily_top_10.csv` — base de dados utilizada
