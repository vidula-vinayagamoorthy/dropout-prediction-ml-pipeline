🎬Dropout Prediction ML Pipeline - Summary
---
Developed prediction on student dropout using supervised learning techniques. Early identification of potential dropouts enables timely interventions, reducing revenue loss, reputational impact, and student dissatisfaction. Model performance is evaluated over multiple stages, with incremental feature enrichment to assess prediction improvements.

✨ Technologies
---
Python (google colab) - numpy, pandas, seaborn, matlplotlib, sklearn, XGBoost, Neural Networks (Keras / TensorFlow)

🚀 Approach
---
Initial steps included exploratory data analysis, feature engineering, and addressing data quality and imbalance. 
Two supervised models were applied: XGBoost and Neural Networks, across three stages of data evolution. 
Each stage involved comparing base models and tuned models, with recall and AUC prioritised (from classification matrix) due to imbalanced data. 
Incremental feature additions were analysed to understand their impact on prediction performance and false negatives.

<img width="680" height="410" alt="image" src="https://github.com/user-attachments/assets/54d31c24-cf13-4556-8c8e-e2f4dece469a" />

🚦 Running the Project
---
The ipynb can be run locally by cloning the file and executing the notebook in a Python environment with the required libraries installed (google colab). 
The notebook is structured sequentially and can be run end‑to‑end.

🎞️ Preview of the output 
--- 
The model was compared across stages for accuracy, recall, AUC, confusion matrices, ROC curves, loss curves, and feature importance plots for XGBoost. 
The tuned XGBoost model on Stage 3 data delivers the strongest overall performance, with the lowest number of missed dropout predictions.

🔭 Why this project? 
--- 
From a technology risk perspective, early risk detection and how we can intervene early can be seen. It highlights practical trade-offs and shows how prediction capability improves as data maturity increases. It also shows the different metrics that can be used for model performances. 

:tada:
