# Churn-prediction-with-Keras
This project demonstrates how to handle imbalanced datasets using Keras. 
It explores different model training strategies aligned with potential business objectives an enterprise might have to prevent customer churn. 
One advantage of using neural networks in this context is their ability to achieve higher recall and greater flexibility in optimizing 
loss functions compared to logistic regression. 
The dataset employed for training the model was sourced from: 
**[Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)**

---

## 📑 Table of Contents
- Loading and exploring Dataset.
- Class Distribution & Strategic Modeling Focus
- Pre-processing and scalinf of the data
- Construction of the model with Keras
- Importance of class weights
- Metrics (Quick evaluation metrics)
- Improvement of the model metrics
  - Correlation between features & Variance
  - Permutation importance
  - SHAP
  - Class Weight calibration
  - Decision Threshold

---

## 🧩 Project Appendix
- Manual training with TensorFlow
    - Import training & test sets from Main notebook
    - Manual configuration
    - Evaluation of the model against Keras
 
---

## 🧰 Technologies and Tools
- Python
- pandas
- numpy
- random
- matplotlib
- seaborn
- scikitlearn
- tensorflow
- keras
- shap

---

## 📂 How to Use This Repository

You can explore the full analysis, visualizations, and conclusions in the PDF document:  
**[Churn prediction with Keras](https://)**  
This version was exported directly from the original Jupyter Notebook using LaTeX.

You may also browse the `/img` folder to preview the key plots separately.

In the [project appendix](https://) you will find a version of the model using manual training
just to demonstreate how it can be done purely TensorFlow.

To explore the original datasets, refer to the links mentioned in the PDF report.
