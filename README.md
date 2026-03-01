# 🛍️ ShopSmart Purchase Prediction using Decision Tree

## 📌 Problem Statement

ShopSmart, an e-commerce company, wants to predict whether a visitor will make a purchase based on their browsing behavior.

The dataset contains **12,330 user sessions** with features like page visits, time spent, bounce rates, and visitor type. The goal is to build a machine learning model that can accurately predict purchase intent.

---

## 🎯 Objective

* Build a **Decision Tree Classifier** to predict whether a user will generate revenue.
* Improve model performance using **pruning techniques**.
* Evaluate performance using **F1 Score** due to class imbalance.

---

## 📊 Dataset Features

* Administrative, Informational, ProductRelated (page visits)
* Duration features (time spent)
* BounceRates, ExitRates
* PageValues
* SpecialDay
* Month
* OperatingSystems, Browser, Region, TrafficType
* VisitorType
* Weekend
* **Revenue (Target Variable)**

---

## ⚙️ Approach

1. Data Understanding
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing

   * Encoding categorical variables
   * Train-test split
4. Model Training

   * Decision Tree (baseline)
5. Model Optimization

   * Pre-pruning (`max_depth`)
   * Post-pruning (`ccp_alpha`)
6. Model Evaluation

---

## 📈 Evaluation Metric

* **F1 Score** (used due to imbalanced dataset)

---

## 🧠 Model Used

* Decision Tree Classifier
* Pruning Techniques:

  * `max_depth`
  * `ccp_alpha`

---

## 🏁 Results

* Final F1 Score: **0.6457142857142857**
* Improved performance after pruning
* Reduced overfitting

---

## 📊 Key Insights

* Users spending more time on product pages are more likely to purchase
* Higher PageValues strongly indicate buying intent
* High BounceRates and ExitRates reduce conversions

---

## 💼 Business Impact

* Helps identify potential buyers
* Enables targeted marketing
* Improves conversion rates
* Reduces marketing costs

---

## 🚀 Future Improvements

* Use advanced models (Random Forest, XGBoost)
* Hyperparameter tuning (GridSearchCV)
* Handle imbalance using SMOTE

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## 📁 Project Structure

```
shop-smart-decision-tree/
│
├── shop_smart_project.ipynb
├── shop_smart_ecommerce.csv
├── README.md
└── requirements.txt
```

---

## 👨‍💻 Author

Lakshay Bamel
