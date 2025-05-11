# 🧬 CodeTheGenome

**Genetic Variant Classification Using Machine Learning**

This project aims to classify genetic variants using publicly available data from [ClinVar](https://www.kaggle.com/datasets/kevinarvai/clinvar-conflicting/data), a comprehensive resource linking genetic variations to diseases. The goal is to develop a predictive machine learning model to categorize variants into clinically meaningful classes, such as **benign**, **pathogenic**, or **uncertain significance**.

---

## Background

Genetic variants are typically classified by clinical labs into the following categories:

- **Benign**
- **Likely Benign**
- **Uncertain Significance**
- **Likely Pathogenic**
- **Pathogenic**

Discrepancies in interpretation can complicate clinical decisions. This project leverages machine learning to provide consistent and data-driven support for variant classification.

---

## Features

- ✅ Data preprocessing and cleaning of genetic variant records  
- 📉 Visualization of missing data patterns using `missingno`  
- 🔠 Categorical feature encoding with `category_encoders`  
- ⚙️ Classification with `CatBoostClassifier`, `XGBoost`, and `LightGBM`  
- 📊 Model evaluation with accuracy scores and confusion matrices  

---

## Installation & Requirements

Install the core Python libraries:

```bash
pip install catboost category_encoders
```

## Additional Dependencies
```bash
pip install pandas numpy matplotlib seaborn missingno
```
---
## Models Used
The project utilizes gradient boosting models known for their efficiency and accuracy in handling structured and categorical data:
- CatBoost
- XGBoost
- LightGBM

## Evaluation & Results
The models are evaluated using:
- ✅ Accuracy Score
- 🔁 Confusion Matrix
- 📉 (Optional) ROC-AUC and other classification metrics

You can run the notebook end-to-end to reproduce the results, from preprocessing to final evaluation.

---
## Dataset
The project uses variant data from ClinVar, which is available through
- [ClinVar Database](https://www.kaggle.com/datasets/kevinarvai/clinvar-conflicting/data)

## License
This project is intended for educational and research use only. Please adhere to ClinVar's data usage policies.






