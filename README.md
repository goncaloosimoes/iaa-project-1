# Previsão de Abandono Académico

Projeto final de Introdução à Aprendizagem Automática.

O objetivo é prever risco de abandono académico a partir de dados de estudantes. A formulação principal é binária: `Dropout` vs `Non-Dropout`. O notebook também inclui uma análise multiclasse com `Dropout`, `Enrolled` e `Graduate`.

Dataset: https://www.kaggle.com/code/jeevabharathis/student-dropout-analysis-for-school-education

## Ficheiros

- `notebook.ipynb`: análise, treino, avaliação e interpretação dos modelos.
- `data/dataset.csv`: dataset usado no projeto.
- `README.md`: resumo e instruções.

## Como Executar

1. Confirmar que `data/dataset.csv` existe.
2. Abrir `notebook.ipynb` no Jupyter.
3. Executar as células pela ordem.

## Conteúdo Principal

- Pipeline de carregamento e pré-processamento dos dados.
- Análise exploratória e distribuição da variável alvo.
- Comparação de modelos com validação cruzada estratificada.
- Baseline, métricas de avaliação e matriz de confusão.
- Discussão de overfitting/underfitting.
- Importância das variáveis e análise por subgrupos.
- Reflexão sobre limitações e uso ético do modelo.
