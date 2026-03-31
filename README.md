# 🔍 Credit Card Fraud Detection with Machine Learning

Este projeto tem como objetivo detectar fraudes em transações de cartão de crédito utilizando técnicas de Machine Learning, com foco na comparação entre os modelos SVM e XGBoost.

A base de dados apresenta forte desbalanceamento (~0,17% de fraudes), exigindo o uso de técnicas específicas como SMOTE e métricas adequadas para avaliação.

📊 Principais etapas:

* Análise exploratória de dados (EDA)
* Tratamento de desbalanceamento com SMOTE
* Padronização dos dados
* Modelagem com SVM e XGBoost
* Avaliação com métricas robustas (Recall, F1-score, ROC-AUC, PR-AUC)
* Ajuste de threshold para simulação de cenários reais

🏆 Resultado:
O modelo XGBoost apresentou melhor desempenho geral, com maior equilíbrio entre detecção de fraudes e redução de falsos positivos.

💡 Destaque:
O projeto inclui análise de trade-offs entre recall e precisão, simulando decisões reais de negócio no combate a fraudes.

🚀 Tecnologias:
Python | Pandas | Scikit-learn | XGBoost | Imbalanced-learn
