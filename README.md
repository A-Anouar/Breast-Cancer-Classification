# Breast Cancer Predictive Modeling & Feature Analysis 🎗️

## Project Overview
This project leverages machine learning (Random Forest) to predict tumor malignancy with high accuracy. Beyond simple classification, this analysis focuses on **feature importance** to identify key biological markers (e.g., 'Worst Perimeter') driving the diagnosis, bridging the gap between raw data and biological insight.

## Key Results
- **Model Used:** Random Forest Classifier (Ensemble Learning).
- **Accuracy Achieved:** 96.5% on the test set.
- **Key Discovery:** Identified "Worst Perimeter" and "Concave Points" as the most statistically significant features for diagnosis using Gini Impurity analysis.

## Methods & Techniques
- **Statistical Analysis:**
  - Applied inferential statistics to compare distributions between benign and malignant classes.
  - Validated feature significance using statistical hypothesis testing.
- **Machine Learning Workflow:**
  - **Algorithm:** Random Forest (utilizing Decision Trees and Entropy/Gini Index for node splitting).
  - **Optimization:** Hyperparameter tuning to maximize precision and recall.
  - **Evaluation:** Confusion Matrix and ROC-AUC analysis.

## Technologies Used
- **Language:** Python 3.x
- **Libraries:** Pandas, Scikit-learn, Seaborn, Matplotlib.
- **Dataset:** Wisconsin Breast Cancer Dataset (via sklearn).

## How to Run
1. Clone the repository.
2. Install requirements: `pip install pandas scikit-learn matplotlib seaborn`
3. Launch the notebook: `jupyter notebook`
