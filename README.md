# Pandas: Uma_introdução_hands-on com auxílio de IA
Estudando Python Pandas usando dados macroeconômicos do Brasil.

# Projeto de Análise Macroeconômica e Previsão com Python

Um projeto de aprendizado contínuo para a aplicação de técnicas de Data Science, Econometria e Machine Learning na análise e previsão de variáveis macroeconômicas brasileiras.

---

## 📖 Sobre o Projeto

Este repositório documenta uma jornada prática de estudo que evolui desde a manipulação de dados fundamental com a biblioteca **Pandas** até a construção de modelos econométricos e de **Machine Learning** para previsão.

O objetivo principal é criar um ambiente para a análise da economia brasileira, buscando:
* Extrair, tratar e transformar dados de fontes públicas como o BCB e o IBGE.
* Realizar análises exploratórias e visualizações para gerar insights.
* Aplicar modelos econométricos clássicos e, futuramente, modelos de Machine Learning para realizar forecasting.

Este projeto é um trabalho em andamento, refletindo um processo de aprendizado iterativo.

## ⚠️ Status Atual

**Projeto em Desenvolvimento.**

A fase atual está focada na **Coleta de Dados, Tratamento (Data Wrangling) e Análise Exploratória (EDA)**. A base de dados principal está sendo construída e as primeiras análises visuais e de correlação foram concluídas.

## 🚀 Principais Tópicos Abordados (Até o Momento)

-   **Acesso a APIs Públicas:** Conexão direta com os sistemas SGS (BCB) e SIDRA (IBGE) para coleta de dados de maneira eficiente e reprodutível.
-   **Manipulação de Dados com Pandas:**
    -   Limpeza e estruturação de dados.
    -   Tratamento de séries temporais: reamostragem de frequência (`resample`), preenchimento de dados faltantes (`ffill`, `interpolate`), e alinhamento de índices.
-   **Engenharia de Features:**
    -   Cálculo de variações (`.diff()`, `.pct_change()`).
    -   Criação de médias móveis (`.rolling()`) para suavizar séries.
    -   Construção de variáveis econômicas como a Taxa de Juros Real *ex-post*.
-   **Visualização de Dados com Matplotlib e Seaborn:**
    -   Criação de gráficos de linha para análise de séries temporais.
    -   Uso de eixos secundários para comparar variáveis com escalas diferentes.
    -   Visualização de matrizes de correlação com heatmaps.
-   **Análise de Correlação:** Quantificação da correlação cruzada entre as variáveis.

## 🗺️ Próximos Passos (Roadmap)

A evolução deste projeto seguirá as seguintes etapas:

-   [ ] **Adição de Novas Variáveis:** Inclusão de indicadores de atividade econômica (ex: IBC-Br) e preços de commodities.
-   [ ] **Análise Econométrica:** Aprofundamento com testes de estacionariedade e características das séries temporais, como ACF e PACF, entre outras.
-   [ ] **Modelagem Clássica:** Construção e estimação de modelos de previsão como ARIMA/SARIMA.
-   [ ] **Modelagem com Machine Learning:** Aplicação de modelos como Lasso, Random Forest e XGBoost para tarefas de forecasting.
-   [ ] **Estudos de Caso e Acompanhamento da conjuntura econômica brasileira e internacional:** Criação de estudos econômicos (ex: "Qual o impacto de um choque nos juros americanos sobre as variáveis brasileiras?") e acompanhamento de conjuntura, atualizando as bases com os dados mais recentes.

## 🛠️ Ferramentas e Bibliotecas

* **Linguagem:** Python
* **Bibliotecas Principais:**
    * **Pandas:** Para manipulação e análise de dados.
    * **Matplotlib & Seaborn:** Para visualização de dados.
    * **python-bcb & sidrapy:** Para acesso às APIs do Banco Central e IBGE.
    * **Numpy:** Para computação numérica. (futuramente)


## Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.