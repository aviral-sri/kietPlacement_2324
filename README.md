# 📊 KIET Placement Analysis 2023–24

This project analyzes the 2023–24 placement data from KIET Group of Institutions using Python, providing insights on company-wise offers, department-wise performance, and salary trends.

## 🧠 Objective

To explore and visualize placement trends across different branches, companies, and salary packages in order to:
- Identify top-performing departments
- Understand CTC (salary) distribution
- Highlight companies offering high packages

## 🗂️ Files

- **`kiet placement 23-24.xlsx`** – Raw placement data
- **`Analysis Notebook.ipynb`** – Jupyter notebook with all code, cleaning, analysis, and visualizations

## 📦 Tech Stack

- **Python**
  - `pandas` – Data processing
  - `numpy` – Numerical computations
  - `matplotlib` & `seaborn` – Visualizations
  - `re` – Regular expressions for cleaning

## 🔍 Key Features

- 📑 **Data Cleaning**
  - Renaming columns
  - Removing email addresses from company names
  - Handling missing or inconsistent entries

- 📈 **Statistical Analysis**
  - Average, max, and min package per branch
  - Count of offers by branch
  - Grouped salary bins (e.g., 1–3 LPA, 3–6 LPA)

- 🎨 **Visualizations**
  - Horizontal bar charts for average, max, min packages
  - CTC distribution with count annotations
  - Heatmap of total offers by branch
  - Top companies with average CTC >10 LPA

## 📊 CTC Binning Logic

Packages are grouped into bins:
- `1–3 LPA`
- `3–6 LPA`
- `6–8 LPA`
- `8–10 LPA`
- `10–13 LPA`
- `13–20 LPA`
- `20–40 LPA`

This helps in visualizing the distribution of offers in meaningful ranges.

## 🚀 How to Run

1. Clone/download this repo and open the notebook in Jupyter or Google Colab.
2. Ensure the Excel file is in the same directory.
3. Install the required packages if not already installed:

```bash
pip install pandas numpy matplotlib seaborn openpyxl
