# 📊 Statistical Analyzer

## 📌 Description
An interactive data analysis and hypothesis testing tool. Users can upload CSV data, perform profiling, and apply statistical tests like T-test and Z-test.

## ✅ Features
- CSV file upload and ETL
- Data profiling using Pandas, Seaborn, and Matplotlib
- T-test and Z-test on selected columns

## 🛠️ Requirements
- Python 3.x
- pandas
- numpy
- scipy
- statsmodels
- matplotlib
- seaborn

## 📦 Install
```bash
pip install pandas numpy scipy statsmodels matplotlib seaborn
```

## 🚀 How to Use (Recommended in Google Colab)
1. Upload CSV using:
```python
from google.colab import files
uploaded = files.upload()
```
2. Perform profiling and select columns.
3. Choose test: `stats.ttest_ind()` or `ztest()`.

## 📂 Output
- Summary statistics
- Graphs (boxplot, histogram)
- T-test or Z-test result with p-value

## 👨‍💻 Author
Avi Vishwakarma
