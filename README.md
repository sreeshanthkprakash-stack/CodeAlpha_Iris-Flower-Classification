# 🌸 Iris Flower Classification

A machine learning project to classify iris flower species (**Iris-setosa**, **Iris-versicolor**, and **Iris-virginica**) based on their morphological measurements (sepal length, sepal width, petal length, and petal width).

This project was developed as part of the **CodeAlpha Data Science / Machine Learning Internship**.

---

## 📌 Project Overview

The Iris flower dataset is one of the most famous datasets in pattern recognition and machine learning. The goal is to build a classification model that can accurately predict the species of an iris flower based on four physical measurements.

### 🌿 Dataset Features

The dataset (`Iris.csv`) contains 150 records with the following attributes:

| Feature | Description |
| :--- | :--- |
| `Id` | Unique identifier for each sample |
| `SepalLengthCm` | Length of the sepal in centimeters |
| `SepalWidthCm` | Width of the sepal in centimeters |
| `PetalLengthCm` | Length of the petal in centimeters |
| `PetalWidthCm` | Width of the petal in centimeters |
| `Species` | Target class: `Iris-setosa`, `Iris-versicolor`, `Iris-virginica` |

---

## 🛠️ Tech Stack & Dependencies

- **Language:** Python 3.13+
- **Environment & Package Manager:** [uv](https://github.com/astral-sh/uv)
- **Core Libraries:**
  - `pandas` — Data manipulation and analysis
  - `numpy` — Numerical operations
  - `matplotlib` & `seaborn` — Exploratory Data Analysis & Visualizations
  - `scikit-learn` — Model training, evaluation, and metrics
  - `ipykernel` — Jupyter notebook kernel

---

## 📁 Project Structure

```text
Iris classification/
├── .venv/                   # Virtual environment
├── src/
│   └── iris_classification/ # Source package
├── Iris.csv                 # Iris dataset
├── main.ipynb               # Jupyter notebook with EDA & model training
├── pyproject.toml           # Project metadata & dependencies (uv)
├── requirements.txt         # Pip dependency requirements
├── uv.lock                  # Lockfile for reproducible builds
└── README.md                # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/sreeshanthkprakash-stack/CodeAlpha_Iris-Flower-Classification.git
cd CodeAlpha_Iris-Flower-Classification
```

### 2. Set Up the Environment

#### Using `uv` (Recommended):
```bash
# Create and activate virtual environment
uv venv
.venv\Scripts\activate   # On Windows
# source .venv/bin/activate  # On Linux/macOS

# Install dependencies
uv sync
```

#### Using `pip`:
```bash
python -m venv .venv
.venv\Scripts\activate   # On Windows
# source .venv/bin/activate  # On Linux/macOS

pip install -r requirements.txt
```

### 3. Run the Project

Open and run the notebook `main.ipynb` in VS Code or Jupyter Lab:

```bash
jupyter notebook main.ipynb
```

---

## 📊 Workflow & Methodology

1. **Exploratory Data Analysis (EDA):**
   - Summary statistics and missing value checks.
   - Pairplots, scatter plots, and correlation heatmaps to understand feature distributions.
2. **Data Preprocessing:**
   - Feature selection (dropping irrelevant columns like `Id`).
   - Feature scaling and train-test splitting.
3. **Model Training & Evaluation:**
   - Training classification algorithms (Logistic Regression, Decision Trees, KNN, Random Forest, SVM).
   - Evaluating performance using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.

---

## 👤 Author

- **Sreeshanth K Prakash** - [@sreeshanthkprakash-stack](https://github.com/sreeshanthkprakash-stack)
- Email: sreeshanthkprakash@gmail.com
