# Walmart Sales Analysis - Python Portfolio Project

## Project Overview
Analysis of Walmart sales data (45 stores, 99 departments, 2010-2012) examining how store size, economic factors (unemployment, CPI, fuel prices), weather, and holidays impact weekly sales. Includes baseline forecasting with year-over-year comparison.

## Key Analyses Performed

### Store Performance
- **Size Impact**: Big stores generate highest weekly sales
- **Type Comparison**: Store Type A outperforms Types B and C

### Economic Factors
- **Unemployment**: Low unemployment = higher sales (12% difference)
- **CPI & Fuel Prices**: Minimal impact on sales volume

### Weather & Holidays
- **Temperature**: Sales by cold/mild/hot weather
- **Holiday Lift**: Holiday weeks generate 15-20% more sales

### Department Analysis
- **Most Predictable**: Department 5 (Hobbies) - 8% forecast error
- **Most Volatile**: Department 95 (Unknown) - 45% error
- **Sales Variance**: Identified high and low volatility departments

### Forecasting Baseline
- **Year-over-Year**: 52-week lag as naive forecast
- **Average Error**: $1,847 absolute | 18.5% percent error

### Promo Analysis
- Markdown effectiveness by department
- Promo vs non-promo week sales comparison

## Key Findings

1. Big stores generate 35% more sales than small stores
2. Low unemployment correlates with 12% higher sales
3. Holiday weeks generate 18% more sales on average
4. Department 5 is most predictable for forecasting
5. Simple year-over-year forecast achieves 81.5% accuracy

## Skills Demonstrated

### Python & Pandas
- Merging multiple datasets
- Date handling and conversion
- Pivot tables and groupby operations
- Custom binning with cut/qcut

### Feature Engineering
- Lag features (1, 4, 52 weeks)
- Store size segmentation
- Temperature and fuel price bucketing

### Analysis Techniques
- Correlation analysis
- Coefficient of variation (CV) for volatility
- Error metrics (absolute, percent error)

### Visualization
- Bar charts with matplotlib
- Scatter plots for distribution analysis

## Files
- `walmart_sales_analysis.ipynb` - Complete Jupyter notebook with all code and outputs
- `README.md` - Project documentation

## Data Source
Walmart Store Sales Forecasting Dataset (Kaggle)

## How to View
1. Open `walmart_sales_analysis.ipynb` in Jupyter Notebook or GitHub
2. All outputs are visible - no need to run code
3. Notebook shows step-by-step analysis with comments

## Author
Data Analyst Portfolio Project
