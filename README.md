# Decision-Tree-ML
Decision Tree model using Scikit-learn

# 🌳 Decision Tree Model using Scikit-learn

## 📌 Project Overview
This project demonstrates the implementation, visualization, and analysis of a **Decision Tree machine learning model** using **Scikit-learn**.  
The model is trained on the **Iris dataset** to classify flower species based on their physical features.

---

## 🎯 Objective
- Build a Decision Tree model for classification
- Visualize the trained Decision Tree
- Evaluate model performance
- Analyze overfitting and feature importance
- Maintain clean, well-commented, and readable code

---

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📊 Dataset
- **Iris Dataset** (built-in dataset from Scikit-learn)
- Features:
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width
- Target classes:
  - Setosa
  - Versicolor
  - Virginica

---

## 🔍 Project Workflow
1. Import required libraries
2. Load and explore the dataset
3. Split data into training and testing sets
4. Train a Decision Tree classifier
5. Visualize the Decision Tree
6. Evaluate model performance
7. Analyze results and overfitting

---

## 📈 Results
- **Training Accuracy:** ~95.8%
- **Testing Accuracy:** 100%
- The model generalized well on unseen data
- Petal width and petal length were the most influential features

---

## 🌿 Model Visualization
The Decision Tree visualization clearly shows:
- Feature-based splits
- Gini impurity at each node
- Class predictions at leaf nodes

This makes the model highly interpretable.

---

## ⚠️ Overfitting Control
To prevent overfitting:
- Tree depth was limited using the `max_depth` parameter
- Training and testing accuracy were compared

