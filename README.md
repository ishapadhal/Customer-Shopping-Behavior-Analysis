# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview

This project focuses on analyzing customer shopping behavior using Python and data analytics techniques. The objective is to explore customer purchasing patterns, understand consumer preferences, identify shopping trends, and uncover actionable business insights.

The analysis uses a customer shopping dataset containing demographic information, purchase history, product categories, spending behavior, discounts, subscription status, and customer reviews.

## 🎯 Project Objectives

- Analyze customer purchasing patterns and spending habits.
- Understand the relationship between demographics and purchasing behavior.
- Identify popular product categories and seasonal shopping trends.
- Examine the impact of discounts and promotional codes.
- Explore customer subscription and loyalty behavior.
- Generate data-driven insights to support business decisions.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data analysis |
| Pandas | Data manipulation and exploration |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Interactive analysis |
| VS Code | Development environment |

## 📂 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_shopping_behavior.csv
├── README.md
├── .gitignore
└── requirements.txt
```

*The structure above is a suggested repository layout. Include only files and dependencies actually used in the project.*

## 📊 Dataset Description

The dataset contains information about customer shopping activities.

**Key Features:**

- Customer ID
- Age and Gender
- Item Purchased
- Category
- Purchase Amount (USD)
- Location
- Size and Color
- Season
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Promo Code Used
- Previous Purchases
- Payment Method

## 🔍 Data Analysis Workflow

### 1. Data Loading

Import the customer shopping dataset using Pandas.

```python
import pandas as pd

df = pd.read_csv("customer_shopping_behavior.csv")
df.head()
```

### 2. Data Exploration

Understand the dataset structure, column types, and statistical characteristics.

```python
df.shape
df.info()
df.describe()
```

### 3. Data Cleaning

- Identify missing values.
- Check for duplicate records.
- Validate data types.
- Prepare the dataset for analysis.

### 4. Exploratory Data Analysis (EDA)

Explore important customer behavior metrics, including:

- Customer distribution by age and gender.
- Spending across product categories.
- Seasonal purchasing trends.
- Subscription-based purchasing patterns.
- Discount and promotional code usage.
- Customer review ratings.
- Purchase history and customer preferences.

### 5. Data Visualization

Use charts and plots to communicate customer shopping trends and relationships between variables.

## 💡 Business Questions

The project aims to answer questions such as:

1. Which product categories generate the highest sales?
2. What is the average customer purchase amount?
3. How does customer spending vary by age and gender?
4. Which seasons experience the highest shopping activity?
5. Do subscribed customers spend more than non-subscribed customers?
6. How do discounts influence customer purchases?
7. Which shipping methods are most commonly used?
8. How does previous purchase history relate to shopping behavior?

## 🚀 How to Run the Project

**1. Clone the repository**

```bash
git clone https://github.com/YOUR_USERNAME/Customer-Shopping-Behavior-Analysis.git
```

**2. Navigate to the project folder**

```bash
cd Customer-Shopping-Behavior-Analysis
```

**3. Create a virtual environment**

```bash
python -m venv .venv
```

**4. Activate the environment**

Windows:

```powershell
.venv\Scripts\activate
```

**5. Install the required libraries**

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

**6. Launch Jupyter Notebook**

```bash
jupyter notebook
```

Open `Customer_Shopping_Behavior_Analysis.ipynb` and run the notebook cells.

## 📈 Expected Outcomes

This project is designed to help identify:

- High-performing product categories.
- Customer spending patterns.
- Differences in purchasing behavior across demographics.
- Seasonal demand trends.
- Opportunities for customer retention.
- Potential improvements in marketing and promotional strategies.

## 🔮 Future Enhancements

- Build an interactive Power BI dashboard.
- Perform SQL-based business analysis.
- Apply customer segmentation techniques.
- Develop predictive models for customer purchasing behavior.
- Create an interactive Streamlit analytics dashboard.

## 📄 License

This project is intended for educational and portfolio purposes. Dataset usage remains subject to its original license.

---

⭐ If you find this project useful, consider giving the repository a star!
