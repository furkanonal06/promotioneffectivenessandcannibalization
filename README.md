---

# 📊 Invent.AI Case Study – Sales Analysis and Promotion Impact

## Overview

This repository contains the solution to the **Invent.AI Case Study**, which focuses on analyzing sales data to evaluate the impact of various promotions and identify potential cannibalization effects. The project leverages exploratory data analysis (EDA), statistical methods, and machine learning techniques to provide actionable insights and business recommendations.

---

## Objectives

The main objectives of this case study are:
- To analyze historical sales data and detect the impact of different promotional activities.
- To identify potential cannibalization between products and categories during overlapping promotions.
- To segment products and stores to understand sales behavior patterns.
- To develop a predictive model estimating promotion-driven sales effects.
- To provide insights and recommendations that support decision-making regarding future promotional strategies.

---

## Methodology

The analysis followed a structured, step-by-step process:
1. **Data Cleaning & Preprocessing:**  
   Handled missing values, removed outliers, and ensured data consistency.
   
2. **Exploratory Data Analysis (EDA):**  
   - Investigated sales trends over time.
   - Identified top-performing products and stores.
   - Visualized promotion periods and their sales effects.

3. **Product and Store Segmentation:**  
   Clustered products and stores based on sales performance using unsupervised learning techniques.

4. **Promotion Impact Modeling:**  
   Developed a machine learning model to estimate net sales during promotional periods while accounting for potential cannibalization effects.

5. **Evaluation & Validation:**  
   Assessed the model's performance and interpreted the outcomes to derive actionable business insights.

---

## Repository Structure

```
📂 invent-ai-case-study/
│
├── 📄 case_study.ipynb       # Jupyter Notebook with the full analysis
├── 📄 README.md              # Project documentation
├── 📄 requirements.txt       # (Optional) List of required Python packages
└── 📂 data/                  # Dataset files (if applicable)
```

---

## Technologies Used

- **Python 3.9+**
- **Jupyter Notebook**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Data visualization
- **Scikit-learn**, **XGBoost** – Machine learning and clustering
- **Statsmodels** – Statistical analysis

---

## Results & Insights

- Measured the effectiveness of individual promotions.
- Quantified cannibalization effects between overlapping promotional products.
- Provided segmentation of stores and products to tailor future campaigns.
- Developed a predictive model to forecast promotion impacts on net sales.

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/furkanonal06/casestudy.git
   ```
2. Navigate to the project folder:
   ```bash
   cd casestudy
   ```
3. (Optional) Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Open and run the notebook:
   ```bash
   jupyter notebook case_study.ipynb
   ```

---

## Business Value

This analysis assists businesses in:
- Understanding the real impact of promotions on sales.
- Minimizing revenue loss caused by product cannibalization.
- Designing more effective promotional strategies.
- Allocating marketing resources efficiently.

---

## Author

**Furkan Önal**  
Data Science Enthusiast | Business-Focused Analyst  
[LinkedIn](https://www.linkedin.com/in/furkan-onal/)

---
