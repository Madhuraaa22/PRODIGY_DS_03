# PRODIGY_DS_03

## 📌 Task Overview
This repository contains **Task-03** of my Data Science internship with **Prodigy InfoTech**.  
The goal of this task is to **build a Decision Tree Classifier** to predict whether a customer will purchase a product or service based on their **demographic** and **behavioral** data.  
I have used the **Bank Marketing dataset** from the **UCI Machine Learning Repository**.

The main objectives are:
- Preprocess and prepare the dataset for machine learning.
- Train a Decision Tree Classifier model.
- Evaluate the model’s performance and visualize results.

## 📊 Dataset
- **File name:** `bank.csv`
- **Source:** [Bank Marketing Dataset - UCI Repository](https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%203)
- **Description:** Contains customer demographic and behavioral information, along with whether they subscribed to a term deposit (`y`).


## 🛠️ Tools & Libraries Used
- **Google Colab** / **Jupyter Notebook**
- **Python** 3.x
- **Libraries:**
  - `pandas` – Data cleaning and manipulation
  - `numpy` – Numerical computations
  - `matplotlib` – Data visualization
  - `seaborn` – Statistical plots
  - `scikit-learn` – Machine learning model building and evaluation


## 🧹 Data Preprocessing Steps
1. **Handle missing values**  
   - Verified that there were no missing values in the dataset.

2. **Encode categorical variables**  
   - Converted categorical columns such as `job`, `marital`, `education`, `contact`, and `y` into numeric codes using **Label Encoding** or **One-Hot Encoding**.

3. **Feature selection**  
   - Selected relevant features for prediction and removed unnecessary columns.

4. **Train-test split**  
   - Split the dataset into **training (70%)** and **testing (30%)** sets.


## 📊 Model Building
- Used **DecisionTreeClassifier** from `scikit-learn`.
- Tuned hyperparameters such as `max_depth` and `min_samples_split` to avoid overfitting.
- Visualized the decision tree structure for better interpretability.


## 📈 Model Evaluation
- **Accuracy Score:** XX%
- **Precision, Recall, F1-Score** were calculated.
- Confusion Matrix was plotted to evaluate classification performance.
