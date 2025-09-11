🌍 Disaster Relief Fund Allocation Optimization

Optimizing global disaster relief fund distribution using K-Means Clustering & PCA

📌 Overview

In times of disasters and natural calamities, efficient allocation of relief funds is crucial for minimizing impact and ensuring equitable support.
This project leverages unsupervised machine learning techniques — K-Means Clustering and Principal Component Analysis (PCA) — to group countries based on socio-economic indicators and optimize fund allocation.

By clustering countries with similar disaster vulnerability and socio-economic profiles, policymakers and NGOs can make data-driven decisions for better humanitarian outcomes.

🎯 Key Features

✅ Exploratory Data Analysis (EDA): Identified patterns, trends, and outliers across 167 countries
✅ Feature Engineering: Normalized socio-economic and disaster-related indicators
✅ Dimensionality Reduction: Applied PCA to reduce feature space and improve clustering performance
✅ Clustering Optimization: Used Elbow Method & Silhouette Score to determine the optimal number of clusters
✅ Actionable Insights: Generated clusters to guide equitable disaster relief allocation

🧠 Tech Stack

Language: Python 3.x

Libraries & Tools:

pandas, numpy → Data preprocessing

matplotlib, seaborn → EDA & visualization

scikit-learn → K-Means, PCA, evaluation metrics

📊 Methodology

Data Collection → Dataset of 167 countries with socio-economic & disaster data

Data Cleaning & Normalization → Handled missing values, scaled features

Exploratory Data Analysis → Visualized distributions, correlations, and trends

PCA → Reduced dimensions to improve interpretability

K-Means Clustering → Grouped countries into optimal clusters

Cluster Analysis → Interpreted results to suggest fund allocation strategy

📈 Results

Optimal number of clusters determined using Elbow Method & Silhouette Score

Generated cluster profiles for high, medium, and low-risk regions

Produced visualizations (scatter plots, cluster maps) for actionable insights

💡 Potential Use Cases

NGOs planning equitable disaster aid allocation

Governments designing risk-based relief policies

International agencies prioritizing funding for vulnerable regions

📷 Sample Visualizations

(Insert screenshots/plots here — PCA plots, cluster visualizations, EDA graphs)

🚀 How to Run
# Clone this repository
git clone https://github.com/your-username/ReliefFund-Optimizer.git

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Disaster_Relief_Fund_Clustering.ipynb
