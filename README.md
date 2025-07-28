# task-3-SkillCraft
  
**Decision Tree Classifier for Customer Purchase Prediction**

---

## 📌 Task Description  
Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data.

---

## 📝 Overview  
This project implements a machine learning solution using a **Decision Tree Classifier** to predict customer purchases. It leverages Python’s `scikit-learn` library for model building, data preprocessing, and evaluation. The goal is to assist businesses in understanding the purchase intent of their customers based on existing data.

---

## 🗂️ Project Structure

**data/**: Contains all relevant datasets used in the project.
- **decision_tree_classifier.ipynb**: Jupyter Notebook with all code implementation.
- ## 🔧 Steps Performed

### 1. 📊 Data Preparation and Preprocessing
- Merged `list-of-orders`, `order-details`, and `sales-target` datasets.
- Created a **binary target variable** to indicate purchase behavior.
- Selected relevant features (demographic and behavioral).

### 2. 🤖 Model Building and Evaluation
- Split the data into **training and testing** sets.
- Built a **Decision Tree Classifier** using `scikit-learn`.
- Trained the model and evaluated it using:
  - Accuracy Score  
  - Classification Report

### 3. 📈 Visualization and Analysis
- Visualized the Decision Tree.
- Explored **feature importance**.
- Analyzed feature distributions and correlations.

---

## 📚 Tech Stack
- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## ✅ Results
- Model performance metrics like accuracy and F1-score help in assessing the predictive power.
- Feature importance identifies key factors influencing customer purchase decisions.

---

## 🚀 Future Improvements
- Hyperparameter tuning for better accuracy.
- Implement Random Forest or Gradient Boosting for comparison.
- Deploy as a web app using Streamlit or Flask.

---

## 👩‍💻 Author  
**Saniya Chhabra**  
AI/DS Student | GGSIPU  
[LinkedIn](https://www.linkedin.com/in/saniya-chhabra/) | [GitHub](https://github.com/saniyachhabra)

---

⭐ *Feel free to fork this repo, explore the notebook, and suggest improvements!*
