# 🌍 Disaster Relief Fund Allocation Optimization  
**Optimizing global disaster relief fund distribution using K-Means Clustering & PCA**  

---

## 📌 Overview  
In times of disasters and natural calamities, **efficient allocation of relief funds** is crucial for minimizing impact and ensuring equitable support.  
This project leverages **unsupervised machine learning** techniques — **K-Means Clustering** and **Principal Component Analysis (PCA)** — to group countries based on socio-economic indicators and optimize fund allocation.  

By clustering countries with similar disaster vulnerability and socio-economic profiles, policymakers and NGOs can make **data-driven decisions** for better humanitarian outcomes.  

---

## 🎯 Key Features  
- ✅ **Exploratory Data Analysis (EDA):** Identified patterns, trends, and outliers across 167 countries  
- ✅ **Feature Engineering:** Normalized socio-economic and disaster-related indicators  
- ✅ **Dimensionality Reduction:** Applied PCA to reduce feature space and improve clustering performance  
- ✅ **Clustering Optimization:** Used **Elbow Method** & **Silhouette Score** to determine the optimal number of clusters  
- ✅ **Actionable Insights:** Generated clusters to guide equitable disaster relief allocation  

---

## 🧠 Tech Stack  
**Language:** Python   

**Libraries & Tools:**  
- `pandas`, `numpy` → Data preprocessing  
- `matplotlib`, `seaborn` → EDA & visualization  
- `scikit-learn` → K-Means, PCA, evaluation metrics  

---

## 📊 Methodology  
1. **Data Collection**  
   - Dataset of 167 countries with socio-economic & disaster-related indicators  

2. **Data Preprocessing**  
   - Handled missing values  
   - Normalized features using MinMaxScaler/StandardScaler  

3. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions, correlations, and trends  
   - Identified important factors affecting disaster vulnerability  

4. **Dimensionality Reduction**  
   - Applied **Principal Component Analysis (PCA)**  
   - Selected top principal components to reduce dimensionality  

5. **Clustering**  
   - Applied **K-Means Clustering**  
   - Used **Elbow Method** & **Silhouette Score** to choose optimal k  

6. **Results & Insights**  
   - Clustered countries into groups with similar socio-economic and risk profiles  
   - Generated recommendations for equitable fund allocation  

---

## 📈 Results  
- 📌 **Optimal number of clusters:** Determined using Elbow Method & Silhouette Score  
- 📌 **Cluster profiles:** High-risk, medium-risk, and low-risk groups identified  
- 📌 **Visualizations:** PCA scatter plots, cluster visualizations, and EDA charts  


## 💡 Use Cases  
- 🏢 NGOs & Governments → Plan equitable disaster aid allocation  
- 📊 Policy Makers → Design risk-based disaster relief policies  
- 🌐 International Agencies → Prioritize funding for most vulnerable regions  

---

## 📂 Project Structure  


🚀 How to Run
# Clone this repository
git clone https://github.com/your-username/ReliefFund-Optimizer.git

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Disaster_Relief_Fund_Clustering.ipynb
