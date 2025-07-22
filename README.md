# Customer Segmentation 🛍️📊

## Aim of the project 🎯  
As assigned, the aim of the project was to independently select a Kaggle dataset and apply a full machine learning pipeline to demonstrate the competencies and methodologies acquired during the course.


## Description 📝 
## Description 📝  
This project uses the Kaggle “Customer Personality Analysis” dataset (https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis/data) to design and implement a complete customer segmentation pipeline—from data cleaning and feature engineering to unsupervised clustering and visualization—demonstrating best practices in applied machine learning.  
In addition to segmentation, exploration of the dataset (and community discussions) revealed a “Response” feature (1 if the customer accepted the offer in the last campaign, 0 otherwise). A supervised predictive model was therefore developed for this binary classification task, showcasing end-to-end ML workflow.  

The goal of this project is to design and implement a complete customer segmentation pipeline— from data cleaning and feature engineering to unsupervised clustering and visualization—demonstrating best practices in applied machine learning. 
A data-driven customer segmentation solution on a real marketing campaign dataset (~2 200 records, 29 features).  
**Objectives:**  
- Clean and preprocess raw data: handle missing values, remove inconsistencies, engineer key features (total spend, purchase counts, tenure, parental status) 🔧  
- Perform exploratory analysis and correlation studies to understand customer behavior 📊  
- Apply and compare multiple clustering algorithms (K-Means, Agglomerative Clustering, DBSCAN) with PCA for 2D/3D visualization 🔍  
- Validate segment quality via Silhouette and Calinski–Harabasz metrics ✔️  
- Profile and label four actionable segments (“Stars,” “High Potential,” “Need Attention,” “Leaky Bucket”) to inform targeted marketing 🚀  

**Main Results:**  
- Four distinct customer groups with clear profiles and business recommendations  
- Silhouette scores > 0.5 across models, indicating well-separated clusters  
- Visual dashboards illustrating segment distribution in income vs. spend space  

## Technologies Used 💻  
- **Python**  
- **pandas** (data manipulation)  
- **NumPy** (numerical operations)  
- **scikit-learn** (clustering, PCA, validation metrics, SMOTE)  
- **seaborn** & **matplotlib** (visualizations)  
- **plotly** (interactive 3D plots)  

