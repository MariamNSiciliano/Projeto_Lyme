# Projeto_Lyme

# Projeto de Análise de Dados: Incidência da Doença de Lyme
​Este repositório contém um estudo detalhado sobre a Doença de Lyme, utilizando técnicas de Análise Exploratória de Dados (EDA) e Modelagem Preditiva para entender a propagação da doença e prever cenários futuros baseados em dados históricos.
​
# Conteúdo do Notebook
​O projeto está estruturado em etapas que cobrem desde o tratamento inicial até a aplicação de algoritmos de Machine Learning:
​1. Análise Exploratória e Limpeza (EDA)
​- Identificação de tendências geográficas e temporais da doença entre 1992 e 2011.
​- Tratamento de dados e verificação de correlações entre variáveis demográficas.
​- Análise de incidência em diferentes regiões (foco no Nordeste dos EUA).
​
2. Visualização de Dados
​- Geração de gráficos para identificar o crescimento da doença ao longo dos anos.
​- Mapas de calor e gráficos de dispersão para visualizar a densidade de casos por condado.
​
3. Modelagem Preditiva
​- Regressão Linear: Implementação de um modelo para prever a continuidade temporal da incidência.
​- Avaliação de Desempenho: Cálculo de métricas como o MAE (Erro Médio Absoluto) para validar a precisão das previsões.
​- Simulação de Cenários: Testes do modelo em cenários fictícios de alta e baixa incidência.
​
4. Conclusões e Melhorias
​Discussão sobre as limitações do modelo de regressão simples em relação a outliers.
​Sugestões de abordagens mais robustas, como Random Forest Regressor e XGBoost, para lidar com surtos extremos.
​
# Tecnologias Utilizadas
​- Python 3
​- Pandas & NumPy: Manipulação e estruturação dos dados epidemiológicos.
​- Matplotlib & Seaborn: Criação de visualizações estatísticas.
​- Scikit-learn: Implementação de modelos de Machine Learning e métricas de avaliação.
​- Google Colab: Ambiente para desenvolvimento e execução do notebook.
​
#Como Executar
​O projeto foi desenvolvido no Google Colab. Para visualizar e interagir:
​1. Clique no badge "Open In Colab" localizado no início do arquivo .ipynb.
​2. Certifique-se de realizar o upload do dataset necessário mencionado no notebook (Lyme Disease Dataset).
