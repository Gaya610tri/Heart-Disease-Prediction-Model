## Heart Disease Prediction Project

This project involves building a machine learning model to predict the presence of heart disease in patients based on various medical attributes. The data used in this project is sourced from the heart disease dataset.

### Table of Contents

- [Introduction](-Introduction)
- [Dataset](-Dataset)
- [Dependencies](-Dependencies)
- [Project Structure](-Project-Structure)
- [Installation](-Installation)
- [Usage](-Usage)
- [Results](-Results)
- [Contributing](-Contributing)
- [License](-License)

### Introduction

The objective of this project is to develop a logistic regression model to predict heart disease. The dataset contains various features such as age, sex, chest pain type, resting blood pressure, cholesterol levels, and more.

### Dataset

The dataset used in this project is the heart disease dataset taken from Kaggle https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset, which includes the following features:

- age: Age of the patient
- sex: Sex of the patient
- cp: Chest pain type (4 values)
- trestbps: Resting blood pressure
- chol: Serum cholesterol in mg/dl
- fbs: Fasting blood sugar > 120 mg/dl
- restecg: Resting electrocardiographic results
- thalach: Maximum heart rate achieved
- exang: Exercise induced angina
- oldpeak: ST depression induced by exercise relative to rest
- slope: Slope of the peak exercise ST segment
- ca: Number of major vessels (0-3) colored by fluoroscopy
- thal (Thalassemia): 0 = normal; 1 = fixed defect; 2 = reversable defect
- target: Diagnosis of heart disease (0 = no disease, 1 = disease)

### Dependencies

The following Python libraries are required for this project:
```
numpy
pandas
matplotlib
scikit-learn
```

### Project Structure

The project is structured as follows:

```
heart_disease_prediction/
│
├── data/
│   └── heart.csv        # Dataset file
├── notebooks/
│   └── ML project.ipynb # Jupyter notebook with the analysis and model
├── README.md            # Project README file
└── requirements.txt     # List of dependencies
```

### Installation

To install the required dependencies, run:
```
pip install -r requirements.txt
```

### Usage

To run the analysis and train the model, open the ML project.ipynb notebook and run the cells in sequence. 

The notebook includes the following steps:

- Importing the Dependencies
- Data Collection and Processing
- Exploratory Data Analysis
- Data Splitting
- Model Training
- Model Evaluation

### Results

The logistic regression model is evaluated using accuracy score, and the results are documented in the notebook.

### Contributing

Contributions are welcome! Please create a pull request or submit an issue for any improvements or suggestions.

### License

This project is licensed under the MIT License.

