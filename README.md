# LightGBM
Essa pipeline é uma aplicação de aprendizado de máquina para regressão, focada na modelagem preditiva utilizando o algoritmo LightGBM (Light Gradient Boosting Machine)

Ela foi projetada para processar um conjunto de dados tabulares fornecido pelo usuário, explorar hiperparâmetros e avaliar o desempenho do modelo em predições numéricas com alta eficiência e precisão.

Funcionalidades Principais:

Processamento de Dados:
-Importação de dados a partir de arquivos ('.xlsx').
-Separação de variáveis independentes (descritores) e variável dependente (alvo).
-Normalização dos dados para garantir uniformidade nas escalas.

Divisão de Dados:
-Realiza a divisão do conjunto de dados em treinamento (80%) e teste (20%) para validação de desempenho.

Otimização de Hiperparâmetros:
-Utiliza o ('GridSearchCV') para encontrar os melhores parâmetros do modelo LightGBM com base no erro quadrático médio negativo em validação cruzada.
Treinamento e Avaliação do Modelo:

Treina o modelo com os melhores parâmetros encontrados.

Calcula métricas de desempenho no conjunto de treinamento e teste, incluindo:
-Erro Quadrático Médio (MSE).
-Coeficiente de Determinação (R²).
-Erro Absoluto Médio (MAE).

Visualização de Resultados:
-Gera gráficos para comparar previsões do modelo com os valores reais, permitindo uma análise visual da precisão do modelo.

Requisitos:
-Python 3.x com bibliotecas essenciais como ('numpy'), ('pandas'), ('scikit-learn'), ('lightgbm') e ('matplotlib').
-Dados de entrada em formato tabular (Excel).

Este software oferece uma solução poderosa e acessível para análise preditiva, destacando-se pela capacidade de extrair informações valiosas a partir de dados numéricos complexos.
