# 📊 Textile Biofilter Selection using Machine Learning

### 📌 Research Title:
**Machine Learning-Based Biofilter Selection for Textile Wastewater Treatment in Bangladesh**

---

## 📁 Dataset Overview

This repository contains the dataset used in our research for predicting optimal biofilter selection in textile wastewater treatment using various machine learning models.

### 📄 File: `textile_biofilter_realistic.csv`

This dataset includes real-world samples of textile wastewater collected from various sources in Bangladesh. It comprises key physico-chemical parameters and the corresponding most suitable biofilter suggestion based on domain knowledge and model predictions.

### 🔑 Key Features:
- `input_cod`: Chemical Oxygen Demand
- `input_bod`: Biological Oxygen Demand
- `input_tds`: Total Dissolved Solids
- `input_tss`: Total Suspended Solids
- `input_ph`: pH level
- `input_nitrate`: Nitrate concentration
- `input_virus`: Presence of viruses (binary/level)
- `input_bacteria`: Bacterial concentration
- `input_color`: Color intensity of wastewater
- `output_filter`: Recommended Biofilter (target label)

---

## 🤖 Machine Learning Models Used

We trained and evaluated six classification models to identify the best-performing one for accurate biofilter prediction:

| Model             | Accuracy |
|------------------|----------|
| Random Forest     | 94.0%    |
| Decision Tree     | 96.5%    |
| Gradient Boosting | 94.3%    |
| LightGBM          | 98.5%    |
| XGBoost           | 97.0%    |
| SVM               | 59.5%    |

LightGBM yielded the highest accuracy and was selected for final deployment.

---

## 📈 Evaluation Metrics

To assess model performance, the following metrics were used:

- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix
- ROC-AUC Curves
- K-Fold Cross Validation
- Feature Importance Analysis

These metrics provide a robust evaluation of model generalization and predictive power.

---

## 🧪 Research Goals

- Optimize the selection process of biofilters for textile wastewater.
- Minimize manual intervention and promote data-driven treatment solutions.
- Support sustainable industrial practices in Bangladesh.

---

## 🌍 Relevance to SDG 6

This research contributes to **Sustainable Development Goal 6: Clean Water and Sanitation**, by improving wastewater treatment efficiency in the textile sector.

---

## 📚 Citation

If you use this dataset or findings in your work, please cite:

Ahmed, S., Khanom, R., Talukder, S., & Bashed, M. A. (2025). *Machine Learning-Based Biofilter Selection for Textile Wastewater Treatment in Bangladesh*.


