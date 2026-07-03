# 🫀 Heart Disease Classification — Machine Learning Project

This repository contains my hands-on implementation of a **Heart Disease Classification** project based on the  
**Complete Machine Learning and Data Science: Zero to Mastery (ZTM)** course.

The goal is to predict whether a patient has heart disease based on clinical parameters, using a real-world dataset and end-to-end ML workflow.

---

## 🎯 Project Goal

> Given clinical data about a patient, can we predict whether or not they have heart disease?

This is a **binary classification** problem:

- `1` → Heart disease present
- `0` → Heart disease not present

---

## 📚 Repository Structure

```
heart-disease/
│
├── data/
│   └── heart-disease.csv
│
├── images/
│   └── ...
│
├── model/
│   └── heart_disease_log_reg_model.joblib
│
├── heart-disease.jpynb
│
├── environment.yml
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 🔍 Dataset

The dataset contains **303 patients** and **14 features** including:

| Feature    | Description                          |
| ---------- | ------------------------------------ |
| `age`      | Age of the patient                   |
| `sex`      | Sex (1 = male, 0 = female)           |
| `cp`       | Chest pain type                      |
| `trestbps` | Resting blood pressure               |
| `chol`     | Serum cholesterol                    |
| `fbs`      | Fasting blood sugar                  |
| `restecg`  | Resting ECG results                  |
| `thalach`  | Maximum heart rate achieved          |
| `exang`    | Exercise induced angina              |
| `oldpeak`  | ST depression induced by exercise    |
| `slope`    | Slope of peak exercise ST segment    |
| `ca`       | Number of major vessels              |
| `thal`     | Thalassemia type                     |
| `target`   | Heart disease present (1) or not (0) |

---

## 🛠️ Tech Stack

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🤖 Models Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest Classifier

---

## 📊 Workflow

1. Exploratory Data Analysis
2. Data Preprocessing & Feature Engineering
3. Model Training & Hyperparameter Tuning
4. Model Evaluation (Accuracy, Precision, Recall, F1, ROC-AUC)
5. Feature Importance Analysis

---

## 💻 How to Use

### 1️⃣ Clone the repository

```bash
git clone https://github.com/cahangirasgerov2003/heart-disease.git
cd heart-disease
```

### 2️⃣ Create a virtual environment (recommended)

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Mac / Linux**

```bash
source venv/bin/activate
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

Open any `.ipynb` file and start exploring.

---

## 📦 Requirements

All dependencies are listed inside:

```
requirements.txt
```

If needed, regenerate it using:

```bash
pip freeze > requirements.txt
```

---

## 🙏 Acknowledgment

Special thanks to the **Zero to Mastery (ZTM)** team for creating a well-structured and practical course that makes complex machine learning concepts approachable and hands-on.

This repository is for educational and personal learning purposes only.

---

## 📫 Contact

If you have feedback or suggestions:

- Email: **cahangir22asgerov@gmail.com**

---

⭐ If you find this repository helpful, feel free to star it.
