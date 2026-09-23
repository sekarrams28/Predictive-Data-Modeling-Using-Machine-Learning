# Predictive Modeling Using Machine Learning 🌱🤖

A beginner-friendly Machine Learning project that uses the **Iris dataset** and a **Random Forest Classifier** to predict the species of an Iris flower based on user-provided measurements.

## 📌 Project Overview

This project demonstrates the basic workflow of supervised machine learning:

1. Load a dataset
2. Explore the data
3. Split data into training and testing sets
4. Train a Random Forest classification model
5. Evaluate model performance
6. Generate a confusion matrix
7. Generate ROC curves and AUC scores
8. Analyze feature importance
9. Accept user input
10. Predict the flower species

## 🧠 Machine Learning Algorithm

### Random Forest Classifier

Random Forest is a supervised machine learning algorithm that combines multiple decision trees to make predictions.

It is used here for classification of Iris flower species.

## 📊 Dataset

The project uses the **Iris dataset** provided by Scikit-learn.

### Input Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Target Classes

- Setosa
- Versicolor
- Virginica

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## 📁 Project Structure

```text
Predictive-Modeling/
│
├── predictive_model.py
├── README.md
└── .gitignore
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/predictive-modeling.git
```

### 2. Open the project folder

```bash
cd predictive-modeling
```

### 3. Install required libraries

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## ▶️ How to Run

Run the Python program:

```bash
python predictive_model.py
```

The program trains the Random Forest model and then asks the user to enter flower measurements.

Example:

```text
Enter Sepal Length: 5.1
Enter Sepal Width: 3.5
Enter Petal Length: 1.4
Enter Petal Width: 0.2
```

The model then predicts the flower species.

Example output:

```text
========================================
PREDICTION RESULT
========================================

Predicted Flower: setosa

Prediction Probability:

setosa : 100.0 %
versicolor : 0.0 %
virginica : 0.0 %
```

## 📈 Model Evaluation

The project evaluates the trained model using:

### Accuracy

Measures the percentage of correct predictions.

### Classification Report

Displays:

- Precision
- Recall
- F1-score
- Support

### Confusion Matrix

Shows the number of correct and incorrect predictions for each class.

### ROC Curve

Visualizes classification performance across different decision thresholds.

### AUC

Measures the area under the ROC curve.

### Feature Importance

Shows the relative importance of the input features in the Random Forest model.

## 🔄 Machine Learning Workflow

```text
             Iris Dataset
                  ↓
            Data Loading
                  ↓
          Feature Selection
                  ↓
          Train/Test Split
                  ↓
       Random Forest Training
                  ↓
             Prediction
                  ↓
       ┌──────────┼──────────┐
       ↓          ↓          ↓
    Accuracy   Confusion    ROC/AUC
               Matrix
       ↓
 Feature Importance
       ↓
     User Input
       ↓
 Final Flower Prediction
```

## 👨‍💻 User Input

The program accepts four values:

```text
1. Sepal Length
2. Sepal Width
3. Petal Length
4. Petal Width
```

These values are passed to the trained model:

```python
prediction = model.predict(user_data)
```

## 🎯 Expected Outcome

After completing this project, you will understand:

- Supervised Machine Learning
- Classification
- Training and testing datasets
- Random Forest
- Model prediction
- Accuracy evaluation
- Confusion matrices
- ROC curves
- AUC
- Feature importance
- User-input-based prediction

## 🚀 Future Improvements

The project can be extended by adding:

- Decision Tree comparison
- Logistic Regression
- K-Nearest Neighbors
- Model accuracy comparison
- Graphical User Interface
- Streamlit web application
- CSV dataset upload
- Prediction history
- Model saving using Joblib

## 📚 Learning Outcome

This project provides practical experience in building and evaluating a supervised machine learning classification model from start to finish.

## 📄 License

This project is created for educational and learning purposes.
