# Iris Flower Classification using KNN

This project classifies Iris flowers into three species—**Setosa**, **Versicolor**, and **Virginica**—based on sepal and petal measurements using the **K-Nearest Neighbors (KNN)** algorithm.

---

## 📁 Files

- `iris_knn.ipynb` – Jupyter Notebook containing all code and visualizations
- `IRIS.csv` – The dataset used for training and testing
- `requirements.txt` – List of required Python packages

---

## 📊 Dataset

The dataset contains 150 rows and 5 columns:

- Features:
  - `sepal_length`
  - `sepal_width`
  - `petal_length`
  - `petal_width`
- Target:
  - `species`: Setosa, Versicolor, and Virginica

---

## 🔍 Project Goals

- Build a classification model using KNN
- Identify the most significant features influencing classification
- Evaluate the model using accuracy, confusion matrix, and classification report

---

## 🛠️ Tech Stack

- Python 3.11.5
- Jupyter Notebook
- scikit-learn
- pandas
- matplotlib
- seaborn

---

## 📈 Model Evaluation

- Accuracy: 100 using K=5
- Metrics used: Accuracy Score, Confusion Matrix, Classification Report
- Visualizations: Correlation Heatmap, Confusion Matrix

---

## ▶️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/iris-knn-classification.git
   cd iris-knn-classification

2. Install dependencies:
   pip install -r requirements.txt

3. Open the Jupyter Notebook:
   jupyter notebook iris_knn.ipynb
