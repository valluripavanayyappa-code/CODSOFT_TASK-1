# CODSOFT_TASK-1
# 🎬 Movie Genre Classification using Machine Learning

## 📌 Overview

This project was developed as **Task 1** for my **CodeSoft Machine Learning Internship**.

The objective is to build a Natural Language Processing (NLP) model that predicts the **genre of a movie** based on its plot summary. The project uses **TF-IDF Vectorization** to convert text into numerical features and compares multiple machine learning algorithms to determine the best-performing model.

---

## 🚀 Features

* Text preprocessing using TF-IDF Vectorization
* Multiple machine learning models

  * Naive Bayes
  * Logistic Regression
  * Linear Support Vector Machine (SVM)
* Model performance comparison
* Classification report
* Confusion matrix
* Predict genre for custom movie plots
* Save and load the trained model

---

## 📂 Dataset

**Genre Classification Dataset**

Files used:

* train_data.txt
* test_data.txt
* test_data_solution.txt

Each movie contains:

* Movie ID
* Genre
* Movie Title
* Plot Summary

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

---

## 🤖 Machine Learning Workflow

1. Load the dataset
2. Explore and preprocess the data
3. Convert movie plots into TF-IDF vectors
4. Train multiple classification models
5. Evaluate each model
6. Compare model accuracy
7. Select the best-performing model
8. Predict genres for unseen movie plots
9. Save the trained model for future use

---

## 📊 Models Used

* Multinomial Naive Bayes
* Logistic Regression
* Linear Support Vector Machine (Linear SVM)

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 📁 Project Structure

```
MovieGenreClassification/
│
├── Movie_Genre_Classification.ipynb
├── train_data.txt
├── test_data.txt
├── test_data_solution.txt
├── movie_genre_model.pkl
├── tfidf_vectorizer.pkl
├── README.md
└── requirements.txt
```

---

## 📦 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
joblib
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Upload the dataset.
4. Run all cells in sequence.
5. Enter a custom movie plot to predict its genre.

---

## 🎯 Sample Prediction

**Input Plot**

> A detective investigates a mysterious serial killer who leaves clues at every crime scene.

**Predicted Genre**

> Crime

---

## 📚 Skills Demonstrated

* Natural Language Processing (NLP)
* Text Vectorization (TF-IDF)
* Machine Learning Classification
* Model Evaluation
* Data Visualization
* Python Programming

---

## 👨‍💻 Internship

**CodeSoft Machine Learning Internship**

Task 1 – Movie Genre Classification

---

## ⭐ GitHub

If you found this project helpful, consider giving it a ⭐ on GitHub.
