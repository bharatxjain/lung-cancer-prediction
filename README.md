# LUNG CANCER PREDICTION

## Objective: 
Built an ML-based model for early Lung Cancer Detection, reducing healthcare professionals’ burden by automating diagnosis. 
–   Tools &amp; Technologies used: Python Language and its Libraries, Jupyter Notebook. 
– Obtained test AUC of 0.96 with Random Forest, using RandomizedSearchCV for hyperparameter tuning.


## Dataset

The dataset contains responses from individuals with various health and lifestyle factors. Each row represents one person, and each column is a feature or label.
https://www.kaggle.com/datasets/bharatxjain/lung-cance-prediction-dataset/

Typical features include:

- Age
- Gender
- Smoking habits
- Alcohol consumption
- Anxiety
- Chronic diseases
- Fatigue
- Coughing frequency
- Chest pain

Target variable: `LUNG_CANCER` (Yes/No)

## Workflow

1. **Data Loading**  
   Load dataset from CSV or directly inside the notebook.

2. **Data Preprocessing**
   - Handle missing values
   - Encode categorical variables
   - Feature selection

3. **Model Building**
   - Split data into train/test sets
   - Train a machine learning model (e.g., Logistic Regression, Decision Tree, Random Forest)

4. **Evaluation**
   - Confusion matrix
   - Accuracy score
   - Classification report

5. **Prediction**
   - Predict lung cancer presence for new inputs

## Requirements

Install the following Python packages:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
