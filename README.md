# 🧬 Cancer Cell Classifier – High Accuracy (96%)

This project predicts whether a cell is **cancerous** or **non-cancerous** using the **Support Vector Machine (SVM)** algorithm. The model achieves **over 96% accuracy**, with performance validated using the **F1 Score**, **Jaccard Index**, and **Confusion Matrix**.

---

## 🚀 Project Highlights

- 🔍 **SVM Classification** with multiple kernels (Linear, Polynomial, RBF, Sigmoid)
- 📊 **96%+ Accuracy** on test data
- ✅ Verified using **F1 Score**, **Jaccard Index**, and **Confusion Matrix**
- 📁 Includes dataset and all code in a single Jupyter Notebook (`main.ipynb`)

---

## 📁 Dataset

The dataset is included in this repository (`data.csv`). It contains labeled data for cancerous and non-cancerous cells, with features extracted from cell samples.

---

## 🧠 Algorithm: Support Vector Machine (SVM)

SVM is used because of its effectiveness in high-dimensional spaces and its performance on small to medium-sized datasets like ours.

### 💡 Key Points:
- Projects data into higher-dimensional space using kernel functions
- Separates data using the best possible hyperplane
- Kernels used in this project:
  - **Linear**
  - **Polynomial**
  - **Radial Basis Function (RBF)**
  - **Sigmoid**

---

## 🔧 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 📊 Evaluation Metrics

| Metric           | Description |
|------------------|-------------|
| **Accuracy**     | Overall correctness of the model |
| **F1 Score**     | Balance between precision and recall |
| **Jaccard Index**| Similarity measure between predicted and actual labels |
| **Confusion Matrix** | Breakdown of true positives, false positives, etc. |

---

## 🧪 How to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Cancer-Cell-Classifier-High-Acc.git
   cd Cancer-Cell-Classifier-High-Acc
