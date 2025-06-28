

## 📄 README.md

````markdown
# 🌿 Consumer Behavior Analysis on Eco-Labeling and Personal Values  
**Author:** A. Kabilesh Rajaselvan  
**Reg. No:** 21MIA1132  
**Institution:** VIT Chennai – SCOPE School  
**Course:** Marketing Analytics  

---

## 🧠 Objective  
To analyze the impact of consumers' personal values and eco-labeling perceptions on their **Willingness to Pay (WTP)** for sustainable products, using regression, classification, and clustering techniques on survey data.

---

## 🎯 Key Concepts  

- Exploratory Data Analysis (EDA)  
- Multiple Linear Regression  
- Logistic Regression Classification  
- Random Forest Regression  
- K-Means Clustering  
- Consumer Persona Profiling  
- Data Visualization & Interpretation  

---

## 🛠️ Tools & Libraries Used  

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Statsmodels**
- **Scikit-learn**

---

## 📁 File Structure  

📦 Eco_Consumer_Analytics  
 ┣ 📜 ma_code.txt               # Full project code for analysis and modeling  
 ┗ 📜 README.md                 # Project documentation  

---

## 🚀 How to Run  

1️⃣ **Clone the repository:**  
```bash
git clone https://github.com/yourusername/Eco_Consumer_Analytics.git
cd Eco_Consumer_Analytics
````

2️⃣ **Install Dependencies:**

```bash
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn
```

3️⃣ **Run the Python Code:**

* Open and run `ma_code.txt` code in your Python IDE or Jupyter Notebook.
* Ensure you have internet access since data is pulled from a Google Sheets CSV URL.

---

## 🔍 Implementation Overview

* **Data Cleaning & Preparation:**

  * Load consumer survey data from Google Sheets
  * Clean column names and handle missing values
  * Create composite scores for personal values and eco-labeling trust
  * Map WTP categorical responses to numeric values

* **EDA & Visualizations:**

  * Histograms, scatter plots, correlation heatmaps, and distribution plots

* **Regression Analysis:**

  * Multiple Linear Regression to predict numeric WTP
  * Logistic Regression to classify consumers into **High** and **Low WTP** groups

* **Clustering & Consumer Segmentation:**

  * K-Means clustering to group consumers based on their value and eco-labeling scores
  * Label clusters with marketing personas:

    * **Eco-Aware Advocates**
    * **Balanced Buyers**
    * **Cost-Conscious Skeptics**

* **Random Forest Regression:**

  * Predict WTP using a Random Forest model
  * Evaluate model performance with R² and RMSE

* **Visualization of Personas and Clusters**

---

## 🧪 Output

* Cleaned and engineered dataset
* Regression models with performance summaries
* Classification accuracy reports and confusion matrix
* Cluster analysis with assigned consumer personas
* Visual plots for distributions, correlations, and clustering patterns

---

## 💡 Applications

* Understand consumer attitudes towards eco-labeling and sustainability
* Segment consumers for targeted marketing strategies
* Predict consumer willingness to pay premium prices for sustainable products
* Build marketing personas for campaign personalization

---

## 📝 Notes

* Ensure internet access to fetch survey data from the provided Google Sheets URL
* The dataset should be formatted as per the expected column names in the code
* Random Forest and K-Means models use default hyperparameters — tuning is recommended for production use
* Additional libraries like `joblib` can be added to save trained models

```


