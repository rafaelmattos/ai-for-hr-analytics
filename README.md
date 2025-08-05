# Employee Attrition Classifier

Este projeto implementa uma análise de dados e modelos de aprendizado de máquina para prever a probabilidade de evasão (demissão voluntária) de funcionários com base em dados históricos da empresa. O objetivo principal é fornecer uma ferramenta analítica capaz de auxiliar a equipe de RH na tomada de decisões estratégicas para retenção de talentos.

## 📊 Sobre o Projeto

A evasão de funcionários pode representar custos significativos para uma organização. Antecipar quais colaboradores estão mais propensos a deixar a empresa permite ações preventivas como treinamentos, ajustes salariais ou mudanças internas.

Este notebook realiza:

- Carregamento e pré-processamento de dados;
- Engenharia de atributos e codificação de variáveis categóricas;
- Criação de diferentes modelos de machine learning;
- Avaliação comparativa de desempenho dos modelos;
- Salvamento do melhor modelo final em disco com `joblib`;
- Demonstração de uso do modelo treinado com dados fictícios.

## 🧠 Modelos Utilizados

Foram treinados e comparados os seguintes classificadores:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- Gradient Boosting Classifier

## 🧪 Avaliação de Desempenho

Os modelos foram avaliados com métricas como:

- Acurácia
- Precisão
- Revocação
- F1-score
- Matriz de Confusão

A escolha final do modelo foi baseada no equilíbrio entre essas métricas, considerando o objetivo de minimizar tanto falsos positivos quanto falsos negativos.

## 📁 Estrutura do Projeto
📦ai-for-hr-analytics

┣ 📜ai-for-hr-analytics.ipynb

┣ 📜employee_model.pkl

┣ 📜README.md


## 🔧 Tecnologias Utilizadas

- Python 3.10
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Joblib

## 💾 Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/ai-for-hr-analytics.git
   cd ai-for-hr-analytics
2. Execute o notebook ai-for-hr-analytics.ipynb no Google Colab ou Jupyter Notebook.

3. Um modelo treinado (employee_model.pkl) será salvo ao final do processo.

4. Você pode testar o modelo com novos dados simulados diretamente no notebook.

##🤖 Próximos Passos
* Implementar uma interface gráfica (Gradio ou Streamlit) para facilitar o uso por usuários não técnicos.

* Melhorar a explicabilidade do modelo com ferramentas como SHAP.

* Automatizar o pipeline com MLFlow ou outro gerenciador de experimentos.

📌 Requisitos
* Python 3.10+

*Bibliotecas listadas no arquivo requirements.txt

👨‍💻 Autor
Rafael Maximino
Desenvolvedor e Cientista de Dados
LinkedIn: linkedin.com/in/rafael-mattos-maximino-135522102/
