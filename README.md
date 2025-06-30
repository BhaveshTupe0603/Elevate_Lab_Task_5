# 🍷 Wine Quality Dataset - Exploratory Data Analysis (EDA)

This project explores the Wine Quality dataset using Python libraries like Pandas, Matplotlib, and Seaborn. The goal is to uncover how various chemical properties of wine influence its quality rating. Through visualizations and statistical analysis, we identify key patterns, trends, and relationships between features.

---

## 🎯 Objective

- Understand the distribution of wine quality ratings
- Analyze how each chemical attribute contributes to wine quality
- Discover patterns and correlations using plots and summary statistics
- Gain insight into which features are most influential in determining wine quality

---

## 📊 Dataset Overview

Each row in the dataset represents a wine sample and includes the following features:

- **fixed acidity**, **volatile acidity**, **citric acid**
- **residual sugar**, **chlorides**
- **free sulfur dioxide**, **total sulfur dioxide**
- **density**, **pH**, **sulphates**
- **alcohol**
- **quality** (Target variable: score between 0 and 10)

This analysis focuses on understanding how these features impact the `quality` of wine.

---

## 🧰 Tools Used

- Python 3
- Pandas – for data handling
- Matplotlib – for basic plotting
- Seaborn – for advanced visualizations

All the code is written in a single Jupyter Notebook that can also be run in Google Colab.

---

## 📈 Key Analysis Performed

- **Data Cleaning**: Checked for null values, duplicates, and removed unnecessary columns (like ID).
- **Univariate Analysis**: Plotted histograms and boxplots to understand distributions of individual features.
- **Bivariate Analysis**: Used boxplots and scatterplots to explore relationships between features and wine quality.
- **Multivariate Analysis**: Used `pairplot()` and correlation heatmaps to visualize interactions between multiple variables.

---

## 🔍 Key Observations & Insights

1. 📊 **Wine Quality Distribution**
   - Most wines are rated **5 or 6**, indicating that the dataset is slightly imbalanced with more average-quality wines.

2. 🍷 **Important Features**
   - **Alcohol** has a strong **positive correlation** with wine quality (correlation = **0.48**).
   - **Volatile acidity** has a **negative correlation** with quality (correlation = **-0.41**).
   - **Sulphates** and **citric acid** also show weak to moderate positive influence on quality.

3. 🧪 **Less Relevant Features**
   - **Residual sugar**, **chlorides**, and **density** had very low or no correlation with quality and are less helpful for prediction.

4. 🧾 **Visual Insights**
   - Boxplots and pairplots clearly show that higher quality wines tend to have:
     - More **alcohol**
     - More **sulphates**
     - Less **volatile acidity**

---

## ✅ Conclusion

The EDA revealed that **alcohol**, **volatile acidity**, and **sulphates** are the most influential factors affecting wine quality. These insights can guide feature selection for future machine learning models and provide useful information for winemaking quality control.

---

## 🙋‍♂️ Author

**Bhavesh Tupe**  
📧 bhaveshtupe06@gmail.com  

---

## 📚 Dataset Source

[UCI Machine Learning Repository – Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)

---
