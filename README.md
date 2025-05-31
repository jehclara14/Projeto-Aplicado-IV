# Projeto Aplicado IV – Previsão e Monitoramento da Epidemia de Dengue

Este repositório reúne os artefatos desenvolvidos no Projeto Aplicado IV do curso de Ciência de Dados da Universidade Presbiteriana Mackenzie, EaD – 2025/01. O objetivo do projeto é construir um modelo de previsão para os casos de dengue no município de São Paulo, utilizando séries temporais semanais e a base de dados pública da API InfoDengue.

## 👩‍💻 Autora

**Jéssica Clara da Silva Santos**

## 📌 Objetivo

Desenvolver um modelo de previsão dos casos de dengue por meio de análise de séries temporais, permitindo identificar tendências, padrões sazonais e anomalias na cidade de São Paulo, a fim de subsidiar ações de prevenção e controle da doença.

## 🗂 Estrutura do Repositório
PROJETO-APLICADO-IV/
├── data/                           # Arquivos de dados e notebook executável
│   ├── dengue_1-18.csv
│   └── Projeto_Aplicado_IV_JessicaClara.ipynb
├── docs/                           # Documentação final
│   ├── PROJETO_APLICADO_IV.docx
│   └── Resultados_Modelagem_ARIMA.docx
├── images/                         # Gráficos e prints utilizados no artigo
│   └── [imagens dos gráficos gerados]
├── Cronograma_Projeto_Aplicado_IV.xlsx
├── requirements.txt               # Lista de dependências do projeto
└── README.md                      # Instruções e apresentação geral do projeto


## 🧪 Tecnologias e Bibliotecas Utilizadas

- Python 3.11+
- Pandas
- NumPy
- Statsmodels
- Matplotlib
- Seaborn
- Scikit-learn

## 🔍 Dados Utilizados

- **Fonte**: API do InfoDengue ([info.dengue.mat.br](https://info.dengue.mat.br/))
- **Cobertura**: Casos semanais estimados e notificados de dengue entre 01/01/2020 e 30/04/2025.
- **Formato**: CSV

## 📈 Principais Etapas

- Extração e organização da base de dados
- Análise exploratória dos dados e visualizações
- Ajuste do modelo ARIMA (1,1,1)
- Avaliação de desempenho: MAE e RMSE
- Geração de previsão para os próximos 10 períodos

## 📊 Resultados

- **Modelo**: ARIMA(1,1,1)
- **MAE** (Erro Médio Absoluto): ~278
- **RMSE** (Raiz do Erro Quadrático Médio): ~1760
- O modelo foi capaz de capturar a tendência de crescimento sazonal e prever com boa aproximação os dados recentes de 2025.

## 📄 Documentação

Todos os detalhes do projeto estão descritos no documento `docs/PROJETO_APLICADO_IV.docx`, incluindo:
- Introdução
- Referencial Teórico
- Metodologia
- Resultados e Discussão
- Conclusão
- Cronograma de Execução
- Referências Bibliográficas (ABNT)

## 🚀 Como Executar

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/jehclara14/Projeto-Aplicado-IV .git
cd PROJETO-APLICADO-IV
pip install -r requirements.txt

Abra o notebook:
jupyter notebook src/Projeto_Aplicado_IV_JessicaClara.ipynb

📎 Licença
Este projeto está licenciado sob os termos da licença MIT.