# Heart Disease Prediction

This repository contains code for predicting the likelihood of heart disease in patients based on medical data. The code uses machine learning techniques to build a predictive model that can classify patients into healthy or affected by heart disease.

## Dataset

The dataset used for training and testing the model is provided in the "data" directory. It contains medical records of patients, including various features such as age, gender, blood pressure, cholesterol levels, and other health indicators.

## Dependencies

Ensure you have the following dependencies installed before running the code:
- Python (version >= 3.6)
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Usage

1. Clone the repository to your local machine:
git clone https://github.com/n-bhakthavathsalam/Heart_Disease_Prediction.git
cd Heart_Disease_Prediction

2. Install the required dependencies:
pip install pandas numpy scikit-learn matplotlib seaborn

3. Run the Python script to train and test the predictive model:
python heart_disease_prediction.py


## Algorithm

The predictive model uses a machine learning algorithm (e.g., Logistic Regression, Random Forest, etc.) to learn patterns from the training data and classify patients into healthy or affected by heart disease. The code includes data preprocessing, feature engineering, and model evaluation steps to ensure accurate predictions.

## Evaluation

The model's performance is evaluated using common classification metrics such as accuracy, precision, recall, and F1-score. The evaluation results and relevant plots are displayed in the console and saved in the "results" directory.

## Results

The final predictions for each patient, along with their corresponding actual labels, are saved in a CSV file named "predictions.csv"
