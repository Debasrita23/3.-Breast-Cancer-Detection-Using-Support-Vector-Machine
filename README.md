Breast Cancer Detection using Support Vector Machine 

This machine learning project uses Support Vector Machines (SVM) to predict whether a breast tumor is benign or malignant, based on numerical features extracted from digitized images. The goal is to assist in early and accurate diagnosis of breast cancer.

📁 Project Files
Breast_Cancer.ipynb – Main notebook with data preprocessing, modeling, and plots

data.csv – Dataset used for training

confusion_matrix.png – Confusion matrix showing prediction results

scatter1.png → scatter4.png – Visual scatter plots for feature relationships

📊 Dataset Details
Source: UCI Breast Cancer Wisconsin (Diagnostic)

Samples: 569

Classes:

M (Malignant) → Encoded as 1

B (Benign) → Encoded as 0

Features: 30 real-valued measurements such as radius, texture, smoothness

⚙️ Workflow Summary
✅ Step 1: Preprocessing
Dropped irrelevant columns

Label encoded target

Scaled features using StandardScaler

✅ Step 2: Model Training
Model: SVM (rbf kernel)

Train/Test Split: 80/20

✅ Step 3: Evaluation
Accuracy: ~98.2%

Confusion Matrix:

📊 Scatter Plots
Each plot shows 2 features colored by diagnosis:
🔵 0 = Benign  🔴 1 = Malignant

1️⃣ concavity_mean vs perimeter_mean

2️⃣ radius_mean vs texture_mean

3️⃣ area_mean vs smoothness_mean

4️⃣ compactness_mean vs concave points_mean


