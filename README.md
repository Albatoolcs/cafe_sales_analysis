# Cafe Sales Analysis & Data Cleaning
This project focuses on inspecting, cleaning, and analyzing a café sales dataset (`dirty_cafe_sales.csv`). It addresses common real-world data issues such as missing values, system-generated errors, and invalid entries, while using Machine Learning to detect transactional anomalies.
 - Key Steps & Methodology:
  1. Data Inspection & Cleaning:
    Handled missing data and corrected invalid text entries (e.g., `ERROR`, `UNKNOWN`).
    Recalculated total sales amounts where information was missing (`Total Spent = Quantity * Price Per Unit`).

  2. Anomaly Detection (Machine Learning):
     Applied the Isolation Forest model to flag irregular purchasing behavior and transactional outliers.

  3. Key Findings & Recommendations:
    Uncovered transactional anomalies caused by arbitrary manual entries or sync glitches.
    Recommended auditing Point of Sale (POS) terminals and cashier devices to ensure accurate future data collection.
- Project Files

 "dirty_cafe_sales.csv": The primary raw sales dataset.
 "Untitled1.ipynb" (or your notebook file): The Jupyter Notebook containing the full Python code for cleaning, analysis, and ML anomaly detection

-How to Run-
1. Clone or download this repository.
2. Place "dirty_cafe_sales.csv" and the `.ipynb` notebook in the same folder.
3. Open and run the notebook in Jupyter Notebook or VS Code.
