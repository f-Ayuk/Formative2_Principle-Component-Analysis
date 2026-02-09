## Formative2_Principle-Component-Analysis

# Principal Component Analysis (PCA) from Scratch using Linear Algebra

## 📌 Overview
This project implements **Principal Component Analysis (PCA) from scratch** using core concepts from **advanced linear algebra**, including:
- Covariance matrices
- Eigenvalues and eigenvectors
- Explained variance
- Dimensionality reduction

The goal is to reduce the dimensionality of a real-world dataset while preserving as much variance as possible, without relying on high-level PCA libraries such as `sklearn`.

This notebook was developed as part of a **Formative Assignment in Advanced Linear Algebra**, with emphasis on mathematical correctness, interpretability, and visualization.

---

## 📂 Project Structure

---

## 📊 Dataset Description
- The dataset used is **African-context aligned** and non-generic.
- It contains:
  - Missing (NaN) values
  - At least one non-numeric column
  - More than 10 features
- Missing values are handled explicitly, and non-numeric columns are excluded before PCA.

---

## ⚙️ Installation Instructions

### 1️⃣ Clone the Repository
```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

numpy
pandas
matplotlib

pip install -r requirements.txt

```
### ▶️ How to Run the Notebook

Option 1: Google Colab (Recommended)

1. Open Google Colab

2. Upload Favor_Ayuk_PCA_Formative_2.ipynb

3. Upload the dataset file (data.csv)

4. Run all cells from top to bottom



Option 2: Using the terminal
```
jupyter notebook

Favor_Ayuk_PCA_Formative_2.ipynb
```
git clone https://github.com/your-username/pca-from-scratch.git
cd pca-from-scratch
