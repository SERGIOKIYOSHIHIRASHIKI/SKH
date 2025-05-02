# SKH
Painel Solar
solar-ai-project/
│
├── README.md                ← Descrição do projeto (já pronta)
├── requirements.txt         ← Lista de bibliotecas necessárias
├── .gitignore               ← Arquivos a serem ignorados pelo Git
│
├── data/                    ← Pasta com os dados brutos ou pré-processados
│   ├── raw/                 ← Dados brutos
│   └── processed/           ← Dados limpos e prontos para modelagem
│
├── notebooks/               ← Jupyter Notebooks para exploração e testes
│   ├── EDA.ipynb            ← Análise exploratória dos dados
│   └── model_tuning.ipynb   ← Ajuste de modelo e validação
│
├── src/                     ← Código-fonte principal
│   ├── __init__.py
│   ├── preprocess.py        ← Funções para limpar e normalizar dados
│   ├── train_model.py       ← Script para treinar os modelos de IA
│   ├── predict.py           ← Predições com novos dados
│   └── evaluate.py          ← Avaliação de desempenho dos modelos
│
├── models/                  ← Modelos treinados salvos (.pkl, .joblib etc.)
│
└── outputs/                 ← Resultados, gráficos, previsões e relatórios
    └── visualizations/
