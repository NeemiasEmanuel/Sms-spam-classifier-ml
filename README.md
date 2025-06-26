# SMS Spam Classifier with Machine Learning

Este projeto foi desenvolvido como parte de um trabalho acadêmico, com o objetivo de construir e comparar modelos de Machine Learning para detecção de mensagens de texto (SMS) classificadas como **spam** ou **não-spam (ham)**.

## 🎯 Objetivo

Aplicar técnicas de pré-processamento de texto e algoritmos de classificação supervisionada para criar modelos capazes de prever, com alta precisão, se uma mensagem SMS é spam ou não.

## 📁 Base de Dados

- Arquivo utilizado: `SMSSpamCollection`
- Formato: `.tsv` com duas colunas (rótulo: "spam"/"ham", texto da mensagem)

## 🧪 Etapas do Projeto

1. **Importação e preparação dos dados**
   - Conversão do rótulo para binário (`1` para spam, `0` para ham)
   - Análise da distribuição das classes

2. **Pré-processamento**
   - Vetorização com TF-IDF para transformar o texto em dados numéricos

3. **Modelagem**
   - **Modelo 1:** Random Forest Classifier
   - **Modelo 2:** Regressão Logística
   - Previsão, cálculo de probabilidades e análise comparativa

4. **Avaliação**
   - Métricas: Accuracy, Precision, Recall, F1-score
   - AUC-ROC e AUC-PR
   - Matrizes de confusão e histogramas de distribuição das probabilidades

5. **Visualizações**
   - Comparação das curvas ROC e Precision-Recall entre os modelos
   - Histogramas para diferentes zonas de decisão

## 📊 Resultados

Ambos os modelos foram treinados e avaliados, com métricas de desempenho e gráficos para facilitar a interpretação:

- **Curvas ROC** e **Precision-Recall** destacam o desempenho dos modelos
- **Histogramas** mostram a distribuição de probabilidade por classe
- **Zonas de decisão** (positiva, neutra e negativa) analisadas estatisticamente

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- Pandas / NumPy
- Scikit-learn
- Matplotlib / Seaborn

## 🚀 Como Executar

1. Faça upload do arquivo `SMSSpamCollection` no ambiente (ex: Google Colab).
2. Execute o script `provads.py`.
3. Visualize os resultados diretamente no console e nos gráficos gerados.

## 👨‍🏫 Autoria

Este projeto foi realizado como parte da disciplina de [Nome da Disciplina] da [Nome da Instituição], com fins acadêmicos.

