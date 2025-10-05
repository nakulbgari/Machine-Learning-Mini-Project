# 🌸 Iris Flower Classification – Mini ML Project

This repository contains a **mini Machine Learning project** where I implemented the classic **Iris Flower Classification** problem using **Python** and **Scikit-learn**.

---

## 📌 Project Overview

The goal of this project is to classify iris flowers into three species (*Setosa, Versicolor, Virginica*) based on their sepal and petal measurements.

### 🔧 Tools & Libraries Used

* **Python 3**
* **Pandas** – data manipulation
* **Scikit-learn** – machine learning algorithms
* **Jupyter Notebook** – interactive coding

---

## 📊 Dataset

* **iris.xlsx** → Training dataset
* **iris_test.xlsx** → Testing dataset
* Features: `Sepal length`, `Sepal width`, `Petal length`, `Petal width`
* Target: `Class` (flower species)

---

## 🚀 Steps Implemented

1. **Data Loading** – Read datasets using Pandas
2. **Feature Selection** – Split into X (features) and y (labels)
3. **Model Training** – Used **Random Forest Classifier**
4. **Prediction** – Predicted species for test dataset
5. **Evaluation** – Checked predictions on unseen data

---

## 📂 Repository Structure

```
📦 Iris-Classification-ML
 ┣ 📜 iris.xlsx              # Training dataset
 ┣ 📜 iris_test.xlsx         # Testing dataset
 ┣ 📜 quick_training_on_iris.ipynb  # Jupyter notebook with full code
 ┗ 📜 README.md              # Project documentation
```

---

## 🧠 Results

* Successfully trained a **Random Forest model**
* Achieved accurate predictions on the test dataset
* Example Prediction:

  ```python
  model.predict([[6, 2.7, 5.1, 1.6]])
  # Output: ['Iris-versicolor']
  ```

---

## 📌 Future Improvements

* Add cross-validation for performance evaluation
* Experiment with other algorithms (Logistic Regression, SVM, etc.)
* Deploy model using Flask/Streamlit

---

## ✨ Motivation

This project is part of my **Winter Arc (1st Oct – 28th Feb 2026)** journey, where I’m consistently building projects to grow in **Data Science and Machine Learning**.

> *"Consistency beats motivation, but when both align—you become unstoppable."*

---

## 🤝 Contributing

Suggestions and improvements are always welcome! Feel free to fork the repo and submit a PR.

---

## 📬 Connect with Me

* LinkedIn: https://www.linkedin.com/in/nakul-bagri-a9b239285/
* Email: ashubagri039@gmail.com

---

# 🔗 Tags

`#Python` `#MachineLearning` `#ScikitLearn` `#DataScience` `#IrisDataset`
