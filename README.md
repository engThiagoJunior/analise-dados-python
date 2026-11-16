# Análise de dados com Python

Projeto de manipulação, visualização e modelagem de dados do Censo Demográfico 2022 (IBGE) e da Divisão Territorial Brasileira 2024, usando pandas, matplotlib, scikit-learn e scipy.

## Estrutura

```
├── etl/          # limpeza e transformação dos dados brutos (executar primeiro)
├── data/         # tabelas usadas nos notebooks (ver dataset.txt)
├── projeto_1/    # pandas + matplotlib: group by, gráficos de linha, barra, pizza, histograma
├── projeto_2/    # PCA, KMeans e regressão linear (scikit-learn)
│   └── resultados/   # figuras e CSVs gerados pelos notebooks
├── dataset.txt   # fontes dos dados
└── requirements.txt
```

## Como executar

1. Instale as dependências: `pip install -r requirements.txt`
2. Rode os notebooks de `etl/` (cada um entra na pasta de dados correspondente).
3. Rode os notebooks de `projeto_1/` e `projeto_2/`.

Os notebooks de `etl/` sobrescrevem os arquivos de `data/`. Se precisar refazer a limpeza, use uma cópia dos arquivos originais do IBGE e da Base dos Dados.

## Fontes

Veja `dataset.txt`.
