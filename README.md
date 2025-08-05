# Retail Sales Performance Dashboard

This project provides a **Retail Sales Performance Dashboard** using **Python** and **Jupyter Notebook**. It visualizes key sales metrics from a retail transactions dataset, helping stakeholders gain insights into revenue, sales trends, and category performance.

---

## Dataset

**Source:** [Retail Transactions Dataset on Kaggle](https://www.kaggle.com/datasets/prasad22/retail-transactions-dataset/data) 
This dataset contains transactional data including:

- `InvoiceNo`
- `Date`
- `Region`
- `Product` and `Category`
- `Quantity` and `UnitPrice`

---

##  Project Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/retail-sales-dashboard.git
cd retail-sales-dashboard
```

### 2. Create a virtual environment 

```bash
python -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate
```

### 3. Install required packages

```bash
pip install -r requirements.txt
```

### 4. How to Run the Project

#### Launch Jupyter Noteboo
```bash
jupyter notebook
```
1. Open Retail_Sales_Analysis.ipynb
2. Run the cells in order to
    *  Load and clean the dataset
    *  Analyze key performance indicators (KPIs)
    *  Visualize:
          * Revenue over time
          * Sales by region
          * Category-wise distribution
          * Average order value
          * Generate summary statistics
     
## Features
*  KPI Dashboard (Revenue, Units Sold, Avg. Order Value)
*  Sales by Region (Bar Chart)
*  Monthly Sales Trend (Line Chart)
*  Category Share (Pie Chart)

## Tools & Libraries Used
1. Python 3.x
2. Pandas: Data manipulation
3. Matplotlib / Seaborn / Plotly: Visualizations
4. Jupyter Notebook: Interactive exploration

