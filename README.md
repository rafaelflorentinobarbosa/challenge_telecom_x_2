📈 Análise de Evasão de Clientes (Churn) - Telecom X
Este projeto tem como objetivo principal analisar a evasão de clientes da Telecom X. Por meio da construção de modelos preditivos, o projeto busca identificar os padrões que levam um cliente a cancelar o serviço e prever a probabilidade de Churn.

1. 📂 Carregamento e Exploração dos Dados
📥 Importação do dataset.

🔍 Análise descritiva inicial (head, shape, info).

⚖️ Verificação da proporção de evasão para avaliar o desequilíbrio de classes.

2. 🛠️ Tratamento e Pré-processamento de Dados
🧹 Remoção de Colunas Irrelevantes: A coluna customerID foi eliminada por ser um identificador único, sem valor preditivo.

✍️ Codificação de Variáveis Categóricas: A transformação das variáveis categóricas foi realizada para torná-las compatíveis com os modelos de machine learning.

🔬 Padronização: A padronização com StandardScaler foi aplicada às variáveis numéricas para preparar o conjunto de dados para o modelo de Regressão Logística.

3. 📉 Análise e Seleção de Variáveis
📈 Análise de Correlação: A matriz de correlação foi calculada e visualizada para entender as relações entre as variáveis e identificar as mais correlacionadas com a evasão.

🗺️ Análises Direcionadas: Gráficos foram gerados para explorar como variáveis específicas, como tempo de contrato e total gasto, se relacionam com a evasão.

4. ✂️ Separação de Dados
Os dados foram divididos em conjuntos de treino (70%) e teste (30%) para garantir que os modelos sejam avaliados em dados não vistos.

5. 🤖 Modelagem Preditiva
Foram treinados dois modelos de classificação para prever o churn:

Regressão Logística:

Motivo: Modelo linear e interpretável, que serve como um bom ponto de partida.

Random Forest:

Motivo: Modelo robusto e poderoso, que geralmente oferece alta performance e reduz o risco de overfitting.

6. 📊 Avaliação de Desempenho e Importância das Variáveis
🎯 Métricas de Avaliação: A performance de cada modelo foi avaliada usando as métricas de Acurácia, Precisão, Recall e F1-score.

🧮 Matriz de Confusão: As matrizes de confusão foram visualizadas para entender a contagem de acertos e erros de cada modelo.

👑 Análise de Importância das Variáveis:

Para a Regressão Logística, os coeficientes das variáveis foram analisados.

Para o Random Forest, a importância intrínseca das variáveis fornecida pelo modelo foi utilizada.

7. 💡 Conclusões e Estratégias de Negócio
Com base nas análises, foi possível identificar os principais fatores que influenciam a evasão de clientes. As conclusões foram usadas para propor estratégias de retenção, como programas de fidelidade e ações proativas para clientes em risco.

💻 Tecnologias Utilizadas
🐍 Python

📚 Pandas, NumPy

🤖 Scikit-learn

📈 Matplotlib, Seaborn

📒 Jupyter Notebook

Autor: Rafael Florentino