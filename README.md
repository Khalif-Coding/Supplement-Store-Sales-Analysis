# 📊 Supplement Store Sales Analysis

## 📂 Repository Outline
```
Milestone1-SupplementSales
│
├── Data_Analysis_Notebook.ipynb 
├── P0M1_Khalif_Santoso_Dataset.csv # Dataset (Supplement Sales) 
└── README.md # Documentation
```


---

## 📌 Problem Background
The management of **Supplement Store A** wants to evaluate the effectiveness of their sales strategy after observing a decline in revenue. This decline appears to be caused by **excessive discounting (over-discounting)** and a **high rate of product returns**.

Key business questions:  
1. Which products are most frequently given high discounts but do not generate significant revenue?  
2. Which category is the best seller in each location?  
3. During which periods do over-discounting and high returns occur most often?  
4. Is there a significant difference in average profit across different sales platforms?  
5. Which products or categories have the highest return rate?  
6. In which regions or platforms are product returns most common?  

---

## 🎯 Project Output
- Insights on sales and discount strategies  
- Data visualizations and analysis  
- Tableau dashboards for management decision-making  

---

## 📊 Data
- **Dataset Link:** [Kaggle – Supplement Sales Data](https://www.kaggle.com/datasets/zahidmughal2343/supplement-sales-data)  
- **Description:** Sales data from a supplement store  
- **Rows:** 4,884  
- **Columns:** 10 (5 numerical, 5 categorical)  
- **Null Values:** 0  

---

## ⚙️ Method
1. Data Visualization  
2. Descriptive Statistics (Central Tendencies)  
3. Inferential Statistics (**ANOVA**)  

---

## 🛠️ Tech Stacks

### 🔹 Libraries
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

from scipy import stats
from scipy.stats import ttest_ind, pearsonr
```

## 📖 References
- [Tableau Dashboard]( https://public.tableau.com/app/profile/ivan.12/viz/Milestone1_17502565662790/SuplementStoreDashboard)
- [EDA](https://towardsdatascience.com/exploratory-data-analysis-8fc1cb20fd15)

