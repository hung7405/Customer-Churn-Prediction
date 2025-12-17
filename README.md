# 📊 Customer Churn Prediction & Analysis (Telecom Industry)

This project performs an in-depth analysis of customer churn behavior within the Telecommunications (Telco) sector. The primary objective is to identify key risk factors leading to service cancellation and build a predictive model to help the business optimize customer retention strategies.

## 🚀 Project Highlights
* **In-depth EDA:** Analyzed correlations between demographics, contract types, and payment behaviors against churn rates.
* **Real-world Data Handling:** Addressed data quality issues including missing values, class imbalance, and categorical encoding.
* **Predictive Modeling:** Implemented Machine Learning algorithms (Logistic Regression, Random Forest) with multi-dimensional evaluation using Confusion Matrices and Classification Reports.
* **Business-Centric Insights:** Translated technical metrics into actionable recommendations for Marketing and Customer Success teams.

## 🛠 Tools & Libraries
* **Language:** Python (Google Colab)
* **Data Manipulation:** `Pandas`, `NumPy`
* **Visualization:** `Matplotlib`, `Seaborn` (Distribution plots, Boxplots, Heatmaps)
* **Machine Learning:** `Scikit-learn` (Pipeline, ColumnTransformer, OneHotEncoder, Random Forest, Logistic Regression)

## 📈 Analysis Workflow

### 1. Data Cleaning
* Converted `TotalCharges` to numeric format and handled null values generated during conversion.
* Verified and handled duplicate records, ensuring data integrity across 7,043 observations.

### 2. Exploratory Data Analysis (EDA)
* **Univariate Analysis:** Identified a baseline churn rate of ~26.5%.
* **Multivariate Analysis:**
    * Discovered a strong correlation between **Contract Type** and churn: Month-to-month customers exhibit significantly higher risk compared to long-term contracts.
    * **Payment Methods:** Customers using Electronic Checks showed the highest propensity to churn.

### 3. Modeling & Evaluation
* Leveraged `ColumnTransformer` and `Pipeline` to automate the feature engineering workflow and prevent data leakage.
* Developed a **Random Forest Classifier** to capture non-linear relationships and identify key feature importance.

## 💡 Key Findings & Recommendations
* **High-Risk Segment:** New customers (short tenure), month-to-month contracts, and Fiber Optic users without value-added services (e.g., Tech Support, Online Security).
* **Actionable Recommendations:**
    * Launch targeted promotional campaigns to transition "Month-to-month" users into 1-2 year contracts.
    * Improve the automated billing experience to reduce friction observed in the Electronic Check segment.

## 📂 Project Structure
* `Customer_Churn_Prediction.ipynb`: Google Colab notebook containing full source code and analysis.
* `Telco_customer_churn_data.csv`: The raw dataset used for the analysis.

---

### How to View
You can open the `.ipynb` file directly in **Google Colab** or **Jupyter Notebook** to walk through the step-by-step process from Data Cleaning to Model Evaluation.
