#  Breast Cancer Detection using Support Vector Machine (SVM)

This machine learning project applies **Support Vector Machines (SVM)** to classify breast tumors as **benign** or **malignant** based on numerical features extracted from digitized images of breast masses. The objective is to support early and reliable diagnosis of breast cancer.

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `Breast_Cancer.ipynb` | Jupyter Notebook with full workflow: preprocessing, modeling, and visualization |
| `data.csv` | Dataset used for training and testing the model |
| `confusion_matrix.png` | Confusion matrix illustrating classification performance |
| `scatter1.png` → `scatter4.png` | Scatter plots showing feature relationships by diagnosis |

---

## 📊 Dataset Details

- **Source**: UCI Breast Cancer Wisconsin (Diagnostic) Dataset  
- **Samples**: 569  
- **Features**: 30 real-valued attributes (e.g., radius, texture, smoothness)  
- **Target Classes**:
  - **M (Malignant)** → Encoded as `1`
  - **B (Benign)** → Encoded as `0`

---

## ⚙️ Workflow Summary

### ✅ Step 1: Preprocessing
- Removed irrelevant columns (e.g., ID)
- Encoded categorical diagnosis labels
- Scaled features using `StandardScaler`

### ✅ Step 2: Model Training
- **Model**: Support Vector Machine (SVM) with **RBF kernel**
- **Train/Test Split**: 80/20

### ✅ Step 3: Evaluation
- **Accuracy**: ~98.2%
- **Confusion Matrix**: Included (`confusion_matrix.png`)  
  Shows excellent separation of benign and malignant classes

---

## 📈 Visualizations

Four scatter plots show relationships between key features, colored by diagnosis:

| Plot | X-axis | Y-axis | Description |
|------|--------|--------|-------------|
| `scatter1.png` | concavity_mean | perimeter_mean | Strong separation between classes |
| `scatter2.png` | radius_mean | texture_mean | Indicates cluster boundaries |
| `scatter3.png` | area_mean | smoothness_mean | Visual class grouping |
| `scatter4.png` | compactness_mean | concave points_mean | Highlights malignancy features |

> 🔵 Benign (0)  🔴 Malignant (1)

---

## 🛠 Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook

```bash
pip install pandas numpy matplotlib seaborn scikit-learn notebook


