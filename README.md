# 🐧 Penguins Species Prediction Using Support Vector Machine (SVM)

## 📘 Overview
This project predicts different penguin species using the **Support Vector Machine (SVM)** algorithm.  
It aims to classify penguins based on measurable physical features such as **bill length**, **bill depth**, **flipper length**, and **body mass**.

## 📊 Dataset
- **Source:** Penguins dataset from **Seaborn** (`sns.load_dataset("penguins")`)  
- **Description:** The dataset contains information about three penguin species — **Adelie**, **Gentoo**, and **Chinstrap** — with various numerical features and categorical data.

## 🧠 Algorithm Used
- **Support Vector Machine (SVM)** for multi-class classification

## ⚙️ Steps Involved
1. Load the Penguins dataset from Seaborn  
2. Handle missing values and encode categorical features  
3. Split the data into training and testing sets  
4. Train the SVM classifier using RBF or linear kernel  
5. Evaluate performance using accuracy, confusion matrix, and classification report  

## 📈 Results
- The SVM model accurately predicts penguin species based on their physical measurements.  
- Demonstrates strong separation between classes in the feature space.

## 🛠️ Tools & Libraries
- Python  
- Scikit-learn  
- Seaborn  
- Pandas  
- NumPy  
- Matplotlib  

## 💡 Key Insight
SVM effectively classifies penguin species by creating decision boundaries that maximize class separation in the feature space.

## 🧾 Author
**Naveen M**
