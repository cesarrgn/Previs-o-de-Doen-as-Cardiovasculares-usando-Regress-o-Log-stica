Descrição do Projeto
Este projeto tem como objetivo prever a probabilidade de um paciente desenvolver doenças cardiovasculares com base em dados clínicos e demográficos. Utilizamos técnicas de análise exploratória de dados (EDA), pré-processamento e um modelo de Regressão Logística para realizar as previsões. O modelo foi avaliado com métricas como acurácia, precisão, recall, f1-score e AUC-ROC.

Dados Utilizados
A base de dados utilizada contém informações sobre pacientes, incluindo:

age: Idade dos pacientes.

gender: Gênero (1 = homem, 2 = mulher).

height: Altura dos pacientes.

weight: Peso dos pacientes.

gluc: Nível de glicose.

smoke: Fumante (1 = sim, 0 = não).

alco: Consumo de álcool (1 = sim, 0 = não).

active: Prática de atividades físicas (1 = sim, 0 = não).

cardio_disease: Presença de doença cardiovascular (1 = sim, 0 = não) - Variável Target.

Passos do Projeto
Carregamento e Tratamento dos Dados:

Verificação de tipos de dados, valores faltantes e outliers.

Correção de valores decimais (substituição de vírgulas por pontos).

Análise Exploratória de Dados (EDA):

Visualização da distribuição de doenças cardiovasculares por gênero, idade e nível de glicose.

Identificação de padrões e insights relevantes.

Matriz de Correlação:

Análise das correlações entre as variáveis para identificar relacionamentos fortes.

Pré-processamento:

Separação dos dados em treino e teste.

Padronização das variáveis numéricas.

Balanceamento dos dados com SMOTE (para tratar desbalanceamento de classes).

Treinamento do Modelo:

Aplicação de um modelo de Regressão Logística.

Avaliação das métricas de desempenho (acurácia, precisão, recall, f1-score).

Teste do Modelo:

Aplicação do modelo aos dados de teste.

Avaliação das métricas de desempenho no conjunto de teste.

Plotagem da curva AUC-ROC.

Conclusões:

Interpretação dos resultados e justificativa do desempenho do modelo.

Tecnologias Utilizadas
Python: Linguagem de programação principal.

Pandas: Manipulação e análise de dados.

Matplotlib e Seaborn: Visualização de dados.

Scikit-learn: Construção e avaliação do modelo de Regressão Logística.

Imbalanced-learn (SMOTE): Balanceamento de dados.

Como Executar o Projeto
Clone o repositório:

bash
Copy
git clone https://github.com/seu-usuario/previsao-doencas-cardiovasculares.git
Instale as dependências:

bash
Copy
pip install -r requirements.txt
Execute o notebook ou script Python:

bash
Copy
jupyter notebook previsao_doencas_cardiovasculares.ipynb
Resultados
O modelo de Regressão Logística obteve os seguintes resultados:

Acurácia no Teste: 85%

Precisão (Classe 1): 0.83

Recall (Classe 1): 0.86

F1-Score (Classe 1): 0.84

AUC-ROC: 0.89

Essas métricas indicam que o modelo tem um bom desempenho na previsão de doenças cardiovasculares.

Próximos Passos
Testar outros algoritmos de classificação, como Random Forest ou XGBoost, para comparar o desempenho.

Coletar mais dados ou variáveis relevantes para melhorar a precisão do modelo.

Implementar o modelo em um sistema de predição em tempo real.

Autor
[Cesar Nunes]
