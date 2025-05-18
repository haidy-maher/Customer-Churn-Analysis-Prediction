# Customer-Churn-Analysis-Prediction

Welcome to the **Customer Churn Data Mining and Predictive Modeling** project! This comprehensive notebook demonstrates an end-to-end data science pipeline applied to customer churn analysis using real-world telecom dataset.

---

## 🚀 Project Overview

This project explores customer churn behavior by applying advanced data mining techniques, exploratory data analysis (EDA), association rule mining, clustering, and multiple classification models. The goal is to gain insights and build robust predictive models that accurately classify customers who are likely to churn.

---

## 📊 Key Features

- **Data Preprocessing & Cleaning**  
  - Handling missing values and data type corrections  
  - Outlier detection and treatment  
  - Encoding categorical variables using Label Encoding and One-Hot Encoding  

- **Exploratory Data Analysis (EDA)**  
  - Visualizations: distributions, boxplots, scatterplots, heatmaps  
  - Statistical tests (Chi-squared) for relationships between categorical variables and churn  

- **Unsupervised Learning**  
  - K-Means clustering on standardized numerical features  
  - Visualization of clusters in 3D space  

- **Association Rule Mining**  
  - Apriori algorithm to extract frequent itemsets  
  - Generation and visualization of top association rules with network graphs  

- **Supervised Learning & Classification Models**  
  - Decision Tree, Random Forest, Logistic Regression, and Neural Network (MLP) classifiers  
  - Performance evaluation with classification reports  

---

## 🛠️ Technologies & Libraries

- Python 3  
- Pandas, NumPy for data manipulation  
- Scikit-learn for modeling and preprocessing  
- Matplotlib, Seaborn for visualization  
- Mlxtend for association rule mining  
- NetworkX for rule graph visualization  
- Google Colab integration for easy execution  

---

## 📁 Repository Structure

- `DATA_MINING.ipynb` — Main Jupyter notebook containing full data analysis, modeling, and visualization workflow  
- `datamining.csv` — Sample telecom customer dataset (path configurable in notebook)  

---

## 🎯 How to Use

1. **Clone this repo** and open `DATA_MINING.ipynb` in Jupyter Notebook or Google Colab.  
2. **Mount your Google Drive** or upload your dataset accordingly.  
3. **Run the notebook cells sequentially** to follow the data mining process from raw data to model evaluation.  
4. **Customize parameters** like clustering number of clusters or model hyperparameters to experiment further.  

---

## 📈 Results & Insights

- Clustering reveals distinct customer segments based on tenure, monthly charges, and total charges.  
- Association rules identify strong relationships between customer service features and churn probability.  
- Classification models, especially Random Forest and Neural Networks, achieve high accuracy in predicting churn, empowering proactive retention strategies.  
