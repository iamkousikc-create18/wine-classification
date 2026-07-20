# 🍷 Wine Classification using Machine Learning

## 📌 Project Overview

This project demonstrates the application of Machine Learning for classifying wines into different categories based on their chemical properties. The project includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and performance comparison using various classification algorithms.

---

## 🎯 Objective

The objective of this project is to build a machine learning classification model that accurately predicts the class of a wine based on its physicochemical attributes.

---

## 📂 Dataset

- **Dataset:** Wine Dataset
- **Source:** Scikit-learn Built-in Dataset
- **Number of Samples:** 178
- **Number of Features:** 13
- **Target Classes:** 3

### Features

- Alcohol
- Malic Acid
- Ash
- Alcalinity of Ash
- Magnesium
- Total Phenols
- Flavanoids
- Nonflavanoid Phenols
- Proanthocyanins
- Color Intensity
- Hue
- OD280/OD315 of Diluted Wines
- Proline

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Project Workflow

- Load the dataset
- Perform Exploratory Data Analysis (EDA)
- Check for missing values
- Visualize feature distributions
- Analyze feature correlations
- Split the dataset into training and testing sets
- Train multiple machine learning models
- Evaluate model performance
- Compare model accuracies
- Select the best-performing model

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Random Forest Classifier

---

## 📈 Model Evaluation

The models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

The Random Forest Classifier achieved the best overall performance for this dataset.

---

## 📁 Repository Structure

```
wine-classification/
│
├── Wine Quality Prediction.ipynb
├── winequality-red.csv
├── requirements.txt
└── README.md
```

---

## ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/wine-classification.git
```

### Navigate to the project folder

```bash
cd wine-classification
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `Wine_Classification.ipynb` and run all cells.

---

## 📌 Results

- Successfully classified wines into three different classes.
- Performed exploratory data analysis and feature visualization.
- Compared multiple classification algorithms.
- Random Forest Classifier provided the highest classification accuracy.

---

## 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Feature importance visualization
- Model deployment using Streamlit
- Cross-validation for improved model reliability

---

## 👨‍💻 Author

**Kousik Chakraborty**

If you found this project useful, feel free to ⭐ this repository.
