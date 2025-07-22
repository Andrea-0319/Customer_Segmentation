# Customer Segmentation 🛍️📊

## Aim of the project 🎯  
As assigned, the aim of the project was to independently select a Kaggle dataset and apply a full machine learning pipeline to demonstrate the competencies and methodologies acquired during the course.


## Description 📝 
This project uses the Kaggle ["Customer Personality Analysis"](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis/data) (~2 200 records, 29 features) dataset to design and implement a complete customer segmentation pipeline—from data cleaning and feature engineering to unsupervised clustering and visualization—demonstrating best practices in applied machine learning.  
In addition to segmentation, exploration of the dataset (and community discussions) revealed a “Response” feature target (1 if the customer accepted the offer in the last campaign, 0 otherwise). A supervised predictive model was therefore developed for this binary classification task, showcasing end-to-end ML workflow.  

**Objectives:**  
- Clean and preprocess raw data: handle missing values, remove inconsistencies, engineer key features 🔧  
- Perform exploratory analysis and correlation studies to understand customer behavior 📊  
- Apply K-Means++ with PCA for 2D/3D visualization 🔍  
- Profile and label four actionable segments (“Stars,” “High Potential,” “Need Attention,” “Leaky Bucket”) to inform targeted marketing 🚀
- Discover and leverage the “Response” column for a supervised task: build and tune a binary classifier to predict campaign acceptance. 🎯


**Main Results:**  
- Four distinct customer groups with clear profiles and business recommendations  
- Visual dashboards illustrating segment distribution in income vs. spend spac
- Developed a predictive model (soft-voting ensemble of Logistic Regression & Random Forest, plus Bagging-DecisionTree) achieving ROC-AUC > 0.96 on held-out data.  


## Technologies Used 💻  
- **Python**  
- **pandas** (data manipulation)  
- **NumPy** (numerical operations)
- **scikit-learn** (K-Means, PCA, supervised models, cross-validation, GridSearchCV, validation metrics)  
- **imbalanced-learn** (SMOTE) for class balancing  
- **seaborn** & **matplotlib** (visualizations)  
- **plotly** (interactive 3D plots)
- **Jupyter Notebook** for exploration, analysis and reporting  
