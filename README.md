# Sales-statistical-data-analysis-task
This GitHub repository contains a sales data analysis project where I performed statistical analysis on sales data for products A, B, C, D, and E. The analysis includes various statistical measures to understand the sales patterns and relationships between different products.
Analysis Techniques Used
Central Tendency Measures:

# 📊 Sales Statistical Data Analysis Project

## 📌 Project Description
This repository contains a comprehensive statistical analysis of sales data for products **A, B, C, D, and E**. The analysis explores sales patterns, variability, and relationships between products using various statistical measures.

## 🔍 Analysis Techniques

### 📈 Central Tendency
- **Mean**: Average sales for each product
- **Median**: Middle value of sales distributions
- **Mode**: Most frequent sales values

### 📉 Dispersion Metrics
- **Standard Deviation (σ)**: Measure of sales volatility
- **Variance (σ²)**: Squared deviation from mean
- **Mean Absolute Deviation (MAD)**: Average absolute difference

### 🔗 Relationship Analysis
- **Correlation Coefficient**: Pearson's r between product sales
- **Comparative Analysis**: Product performance relationships

## 💻 Technologies Used
| Technology | Purpose |
|------------|---------|
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) | Core programming |
| ![NumPy](https://img.shields.io/badge/Numpy-013243?style=flat&logo=numpy&logoColor=white) | Numerical operations |
| ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) | Data manipulation |

# Sales Data Analysis

## Statistical Analysis of Product Sales Data

### Basic Statistics

| Product | Mean | Median | Mode | Variance | Std Dev | Min | Max | Range |
|---------|------|--------|------|----------|---------|-----|-----|-------|
| A       | 15.07 | 15.0 | 15 | 10.30 | 3.21 | 10 | 21 | 11 |
| B       | 10.20 | 10.0 | 10 | 7.27 | 2.70 | 6 | 16 | 10 |
| C       | 7.33 | 7.0 | 5 | 7.47 | 2.73 | 3 | 13 | 10 |
| D       | 24.33 | 25.0 | 25 | 15.82 | 3.98 | 18 | 33 | 15 |
| E       | 5.20 | 5.0 | 5 | 6.86 | 2.62 | 1 | 11 | 10 |

### Correlation Matrix

| Product | A    | B    | C    | D    | E    |
|---------|------|------|------|------|------|
| A       | 1.00 | 0.98 | 0.97 | 0.98 | 0.97 |
| B       | 0.98 | 1.00 | 0.99 | 0.99 | 0.99 |
| C       | 0.97 | 0.99 | 1.00 | 0.99 | 0.99 |
| D       | 0.98 | 0.99 | 0.99 | 1.00 | 0.99 |
| E       | 0.97 | 0.99 | 0.99 | 0.99 | 1.00 |

### Key Insights

1. **Product Performance**:
   - Product D has the highest average daily sales (24.33 units)
   - Product E has the lowest average daily sales (5.20 units)

2. **Sales Consistency**:
   - Product D shows the most variability (Std Dev = 3.98)
   - Product B shows relatively stable sales (Std Dev = 2.70)

3. **Product Relationships**:
   - All products show strong positive correlations (>0.97)
   - When sales increase for one product, they tend to increase for others

4. **Sales Distribution**:
   - Mean ≈ Median for all products, suggesting symmetric distributions
   - No significant skewness in the sales pattern
  
🔑 Key Findings
Product [X] showed highest mean sales (💰 [value])

Strong correlation (r = [value]) between [Product_Y] and [Product_Z]

[Product_A] exhibited lowest variance (σ² = [value])

📅 Future Enhancements
Add interactive visualizations with Plotly

Implement time-series forecasting

Develop automated reporting

## 🚀 How to Run
```bash
git clone https://github.com/Amr0122/sales-analysis.git
cd sales-analysis
pip install numpy pandas
python sales_analysis.py

