\# 🌍 Country Clustering Analysis using K-Means



\## 📌 Overview

This project applies \*\*unsupervised machine learning\*\* to cluster 167 countries based on socio-economic and health indicators such as income, exports, imports, life expectancy, and child mortality. The goal is to discover meaningful patterns between countries using clustering techniques.



\---



\## 🎯 Objective

To group countries into similar clusters in order to better understand global development patterns and economic differences using machine learning.



\---



\## 📊 Dataset

The dataset contains 167 countries with features such as:

\- Income

\- Exports

\- Imports

\- Life expectancy

\- Child mortality

\- Other socio-economic indicators



\---



\## 🧹 Data Preprocessing

\- Explored and visualized the dataset

\- Checked data quality and distribution

\- Detected a high percentage of outliers (\~67%)

\- Kept outliers due to small dataset size (167 rows)

\- Applied feature scaling

\- Used PCA for dimensionality reduction



\---



\## 🤖 Model \& Methods

\- Algorithm: \*\*K-Means Clustering\*\*

\- Dimensionality reduction: \*\*PCA\*\*

\- Cluster evaluation methods:

&#x20; - Elbow Method

&#x20; - Silhouette Score

&#x20; - Calinski-Harabasz Index

&#x20; - Davies-Bouldin Score



\---



\## 📈 Results

\- Most evaluation methods suggested \*\*5 clusters\*\*

\- However, one cluster contained only Nigeria, making it an outlier group

\- Based on the Davies-Bouldin score, \*\*4 clusters\*\* provided better and more realistic results

\- Nigeria was then grouped with other Southern African countries, improving interpretation



\---



\## 🗺️ Visualization

\- Countries were visualized on a world map with cluster coloring

\- A table was created to summarize country groupings



\---



\## 🧠 Conclusion

K-Means clustering successfully grouped countries into meaningful clusters based on socio-economic indicators. Using 4 clusters instead of 5 improved interpretability and produced more realistic global groupings.



\---



\## 🛠️ Tools Used

\- Python

\- Pandas

\- NumPy

\- Matplotlib / Seaborn

\- Scikit-learn

\- PCA

\- K-Means



\---



\## 📚 References

This project was developed as part of a learning journey in Data Science and Machine Learning.



The dataset is originally inspired from Kaggle (no specific link available as the project was completed earlier).



Concepts were learned from online courses (including Udemy Machine Learning courses) and official documentation such as Scikit-learn.



All analysis, preprocessing, modeling, and visualization were implemented independently.



\---



\## 🚀 Author

Data Science \& Machine Learning Enthusiast

