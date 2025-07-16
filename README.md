# 🪨 Rock vs Mine Prediction using Machine Learning

This repository contains a machine learning project that classifies sonar signals as either **Rocks** or **Mines**. It uses data from the UCI Machine Learning Repository and implements a **Logistic Regression** model to perform binary classification.

## 📌 Problem Statement

The goal is to predict whether an object is a **mine** or a **rock** based on sonar energy measurements. This helps in underwater object detection using sonar frequency responses.


## 🧠 Technologies Used

- **Language**: Python 🐍
- **Libraries**:
  - `pandas` – Data manipulation
  - `numpy` – Numerical operations
  - `scikit-learn` – ML algorithms and evaluation


## 📊 Dataset Description

- **Name**: Sonar Dataset
- **Source**: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks))
- **Instances**: 208
- **Features**: 60 numeric attributes (0–1 range)
- **Target**: `'R'` (Rock) or `'M'` (Mine)

Each instance represents sonar readings returned by bouncing sonar signals off surfaces.


## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/rock-vs-mine-prediction.git
cd rock-vs-mine-prediction
```

### 2️⃣ Launch the Notebook
```bash
jupyter notebook Rock_vs_Mine_Prediction.ipynb
```



