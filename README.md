
## 📊 Customer Lifetime Value (CLV) Prediction

This project focuses on analyzing customer behavioral and transactional data to estimate their **Customer Lifetime Value (CLV)** — an important metric for long-term business decision-making in marketing and customer relationship management.

---

### 🔍 Overview

The notebook performs **exploratory data analysis (EDA)**, preprocessing, feature engineering, and regression modeling to predict the lifetime value of customers based on historical marketing and purchase data.

---

### 📁 Files Included

* `Customer_Lifetime_Value_Prediction.ipynb` — Main Jupyter notebook containing the analysis and model.
* `customer_data_internship.csv.gz` — Gzipped dataset file used in the notebook (compressed for efficient storage).
* `.csv.gz` file must be unzipped or read using pandas with `compression='gzip'`.

---

### 📌 Key Features

* 📈 **Exploratory Data Analysis (EDA)**: Understanding data distribution, outliers, correlations.
* 🔧 **Preprocessing**: Handling missing values, encoding categorical variables, scaling.
* 🧠 **Modeling**: Implemented machine learning models like Linear Regression, Random Forest, etc., to predict CLV.
* 📊 **Evaluation**: Used metrics like RMSE and R² Score for model performance assessment.
* 📉 **Feature Importance**: Interpreting the key drivers of customer lifetime value.

---

### 📦 Dependencies

Make sure to install the following libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

If you're using Google Colab, upload the `.csv.gz` file before running the notebook.

---

### 🚀 Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/Shreya7tripathy/Customer-Lifetime-Value-Prediction.git
   cd Customer-Lifetime-Value-Prediction
   ```

2. Run the notebook using Jupyter or Google Colab.

3. Load the compressed dataset:

   ```python
   import pandas as pd
   df = pd.read_csv('customer_data_internship.csv.gz', compression='gzip', encoding='ISO-8859-1')
   ```

---

### 📌 Insights

* Customers with higher total claim amounts, longer tenure, and more interactions tend to have higher predicted CLV.
* Features like `Income`, `Monthly Premium Auto`, and `Customer Lifetime Engagement` showed strong correlations with CLV.
* Ensemble models like **Random Forest** delivered better prediction accuracy compared to simple linear regression.

---

### 📚 Future Work

* Optimize hyperparameters using GridSearchCV.
* Explore advanced regression models like XGBoost or LightGBM.
* Build a web-based dashboard to visualize predicted CLVs for new customer data.

---

### 🙋‍♀️ Author

**Shreya Tripathy**
📌 [GitHub](https://github.com/Shreya7tripathy)
📌 [LinkedIn](https://www.linkedin.com/in/shreyatripathy7/)

---

### ⭐️ Show Some Love

If you found this project helpful, feel free to ⭐️ star the repository and share your thoughts or suggestions via issues or pull requests.

