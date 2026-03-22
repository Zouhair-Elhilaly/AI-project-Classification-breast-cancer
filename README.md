# Breast Cancer Classification using Logistic Regression

## 📌 Project Overview

This project applies **Machine Learning** to classify breast cancer tumors as **malignant** or **benign** using the **Logistic Regression** algorithm.

The model is trained using the **Breast Cancer Wisconsin dataset** available in `scikit-learn`. The goal is to build a simple and interpretable classification model that can assist in understanding how machine learning can support medical diagnosis.

---

## 📊 Dataset

The dataset used in this project is the **Breast Cancer Wisconsin dataset**, which contains:

* **569 samples**
* **30 numerical features**
* Target classes:

  * `0` → Malignant
  * `1` → Benign

Features describe characteristics of cell nuclei present in breast mass images such as:

* Radius
* Texture
* Perimeter
* Area
* Smoothness
* Compactness
* Concavity
* Symmetry

---

## 🧠 Machine Learning Model

The model used in this project is:

**Logistic Regression**

Logistic Regression is commonly used for **binary classification problems**, making it suitable for predicting whether a tumor is malignant or benign.

---

## ⚙️ Project Workflow

The notebook follows these main steps:

1. Import required libraries
2. Load the dataset
3. Explore the data
4. Split dataset into training and testing sets
5. Train a Logistic Regression model
6. Make predictions
7. Evaluate the model performance

---

## 🧪 Model Evaluation

Model performance is evaluated using:

* Accuracy score
* Confusion matrix
* Classification report

These metrics help assess how well the model predicts cancer types.

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn

---

## 📁 Repository Structure

```
AI-project-Classification-breast-cancer
│
├── breast-cancer-classification-LogisticReg.ipynb
├── README.md
```

---

## 🚀 How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/Zouhair-Elhilaly/AI-project-Classification-breast-cancer.git
```

2. Navigate to the project folder

```bash
cd AI-project-Classification-breast-cancer
```

3. Open the notebook

```bash
jupyter notebook
```

4. Run the notebook cells step by step.

---

## 📈 Future Improvements

Possible improvements for this project:

* Add data visualization and exploratory data analysis (EDA)
* Apply feature scaling
* Compare multiple models (SVM, Random Forest, KNN)
* Add ROC Curve and AUC score
* Deploy the model using a web interface

---

## 👨‍💻 Author

**Zouhair Elhilaly**

AI & Machine Learning Student
Interested in Artificial Intelligence, Data Science, and IoT systems.

---

## 📜 License

This project is open source and available under the MIT License.
