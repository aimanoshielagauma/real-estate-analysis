# Real Estate Analytics (Python)

A comprehensive data analysis project focused on evaluating the financial performance of multiple real estate properties using Python.
This project applies data analysis techniques to uncover insights on revenue generation, cost behavior, occupancy trends and investment risk.

## Key Features

* Revenue and cost analysis across properties
* Time-series visualization of performance trends
* Risk modeling using standard deviation
* Best-case and worst-case scenario evaluation
* Data-driven insights for decision making

## Tech Stack

* **Python**
* **Pandas** – data manipulation and analysis
* **NumPy** – numerical computations
* **Matplotlib** – data visualization
* **Jupyter Notebook**


##  Project Structure


real-estate-analytics-python/
│
├── data/
│   └── real_estate_data.csv
│
├── notebooks/
│   └── real_estate_analysis.ipynb
│
├── outputs/
│   ├── occupancy_trend.png
│   ├── revenue_trend.png
│   └── cost_trend.png
│
├── requirements.txt
└── README.md
```

---

##  Analysis Breakdown

### 1. Data Preparation

* Loaded and structured dataset by property (A, B, C)
* Cleaned and organized time-series data

### 2. Financial Metrics

* Average daily revenue
* Monthly cost analysis
* Occupancy rate evaluation

### 3. Profitability Modeling

Estimated annual revenue using:

```
Annual Revenue = (Daily Revenue × Occupancy × 12) − (Monthly Cost × 12)
```

---

### 4. Risk Analysis

Used standard deviation to evaluate variability:

*  Best-case scenario
*  Worst-case scenario

---

##  Visualizations

The project includes trend analysis for:

* Occupancy over time
* Revenue performance
* Cost fluctuations

---

##  Key Insights

* **Property C** generates the highest revenue but also incurs the highest costs, indicating high-risk, high-reward behavior
* **Property B** shows the most stable performance with consistent occupancy
* **Property A** demonstrates moderate profitability with noticeable variability

---

##  How to Run

1. Clone the repository:

```
git clone https://github.com/aimanoshi.elagauma/real-estate-analytics-python.git
```

2. Navigate into the project:

```
cd real-estate-analytics-python
```

3. Install dependencies:

```
pip install -r requirements.txt
```

4. Run Jupyter Notebook:

```
jupyter notebook
```

---

##  Future Improvements

* Add interactive dashboards 
* Build predictive models for revenue forecasting
* Deploy as a web app (Streamlit)

---

## Author

**Aimanoshi Elagauma**
Computer Science Graduate | Data Analyst | Data Engineer (in progress)

---

 If you found this useful, consider giving it a star!
