# Heart Disease Prediction
This project is a machine learning-based analysis to predict the likelihood of heart disease using patient data. The notebook preprocesses data, evaluates multiple machine learning algorithms, and compares their performance to identify the most effective model.

# Project Structure
## Main Components
## Data Loading:

The dataset is loaded and explored for missing or duplicate values.
Columns include patient details such as age, sex, cholesterol levels, and target (heart disease presence).

## Data Preprocessing:

Data cleaning, normalization, and preparation for model training.

## Model Training and Evaluation:

Models tested include:
### Logistic Regression
### Support Vector Machine (SVM)
### K-Nearest Neighbors (KNN)
### Decision Trees
### Random Forest
### Gradient Boosting
### Performance metrics are evaluated and compared.

## Visualization:

Libraries like matplotlib and seaborn are used to generate insights from data.

### How to Use
Clone the repository or download the notebook file.
Ensure the required libraries are installed. Install dependencies using:
bash
Copy code
pip install -r requirements.txt
Run the notebook using Jupyter Notebook or Jupyter Lab:
bash
Copy code
jupyter notebook Heart_Disease_Prediction.ipynb

## Dataset
The dataset contains the following columns:

age: Patient age in years
sex: Gender (1 = male, 0 = female)
cp: Chest pain type (categorical)
trestbps: Resting blood pressure
chol: Serum cholesterol in mg/dl
fbs: Fasting blood sugar (> 120 mg/dl, 1 = true, 0 = false)
restecg: Resting electrocardiographic results
thalach: Maximum heart rate achieved
exang: Exercise-induced angina (1 = yes, 0 = no)
oldpeak: ST depression induced by exercise relative to rest
slope: Slope of the peak exercise ST segment
ca: Number of major vessels (0-3) colored by fluoroscopy
thal: Thalassemia (categorical)
target: Diagnosis of heart disease (1 = disease, 0 = no disease)

## Requirements
The project uses the following libraries:

pandas
numpy
scikit-learn
matplotlib
seaborn
joblib

## Results
The notebook concludes by identifying the best-performing model based on accuracy, precision, and other metrics.
