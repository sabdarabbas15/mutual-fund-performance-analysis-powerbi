# mutual-fund-performance-analysis-powerbi
Power BI project analyzing mutual fund performance, risk metrics, expense ratios, AUM trends, and portfolio allocation using the India Mutual Fund Dataset 2025.
## Project Overview
This project focuses on analyzing the India Mutual Fund Dataset 2025 using Power BI and Python. The objective of the project is to evaluate mutual fund performance, risk metrics, expense ratios, portfolio allocation, and AUM trends through interactive dashboards and business insights.

The project simulates real-world financial analytics and investment analysis performed by data analysts in the finance domain.

---

## Objectives
- Analyze mutual fund performance across different time periods
- Compare risk vs return metrics
- Evaluate expense ratio impact on performance
- Analyze portfolio allocation and sector exposure
- Create professional interactive dashboards in Power BI
- Generate investment insights using DAX measures

---

## Tools & Technologies Used
- Python
- Pandas
- NumPy
- Power BI
- DAX
- CSV Dataset

---

## Dataset Information
Dataset: India Mutual Fund Dataset 2025

The dataset contains:
- Fund performance metrics
- Risk indicators
- Expense ratios
- AUM details
- Portfolio allocation
- Benchmark comparisons
- Fund classifications

---

## Data Cleaning Process
Data preprocessing was performed using Python.

### Cleaning Steps
- Checked missing values
- Removed duplicate rows
- Converted percentage columns into numeric format
- Handled null values
- Converted date columns into datetime format
- Prepared cleaned dataset for Power BI analysis

---

## DAX Measures Created
The following measures were created in Power BI:

- Total Funds
- Total AUM
- Average 1-Year Return
- Average 3-Year Return
- Average 5-Year Return
- Average Expense Ratio
- Average Sharpe Ratio
- Average Alpha
- Average Beta
- Risk Adjusted Return Score
- Fund Ranking Measure

---

## Dashboard Pages

### 1. Executive Overview Dashboard
- Total Funds
- Total AUM
- Avg 3-Year Return
- Avg Expense Ratio
- Category Distribution
- AUM by Category
- Top Performing Funds

### 2. Performance Dashboard
- 1Y vs 3Y vs 5Y Return Comparison
- Long-Term vs Short-Term Returns
- Top Performing Funds
- Return Trend Analysis

### 3. Risk & Volatility Dashboard
- Beta vs Return Scatter Plot
- Sharpe vs Return Analysis
- Standard Deviation Ranking
- Risk Comparison

### 4. Portfolio Composition Dashboard
- Large/Mid/Small Cap Allocation
- Sector Allocation Analysis
- Average Market Cap Analysis
- Stock Distribution

### 5. Ranking & Investment Insights Dashboard
- Custom Fund Ranking
- Top Recommended Funds
- Risk Adjusted Analysis
- Interactive Slicers

---

## Key Business Insights
- Long-term funds showed stronger performance consistency
- High-return funds often carried higher volatility
- Lower expense ratio funds generally performed better
- Large-cap focused funds showed better stability
- IT and Banking sectors dominated equity portfolios

---

## Project Structure

```text
Mutual_Fund_Analysis_Project/
│
├── Dataset/
│   ├── Mutual Fund Dataset 2025.csv
│   └── Mutual_Fund_Cleaned.csv
│
├── Python/
│   └── mutualfund_cleaning.py
│
├── PowerBI/
│   └── Mutual_Fund_Analysis.pbix
│
├── Screenshots/
│   └── Dashboard Images
│
└── README.md
```

---

## Screenshots
(Add your Power BI dashboard screenshots here)

---

## How to Run the Project

### Python
1. Install required libraries:
```bash
pip install pandas numpy
```

2. Run cleaning script:
```bash
python mutualfund_cleaning.py
```

### Power BI
1. Open `.pbix` file
2. Refresh dataset
3. Explore dashboards and insights

---

## Future Improvements
- Add predictive analytics for fund performance
- Integrate live market data
- Add investor recommendation system
- Build machine learning-based risk prediction

---

## Author
Sabdar abbas

---

## Connect With Me
### LinkedIn
(Add your LinkedIn profile link)

### GitHub
(Add your GitHub profile link)
