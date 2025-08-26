# 📊 Ironhack Payments Cohort Analysis

This project analyzes the behavior of users and financial metrics of **Ironhack Payments’ cash advance service** through a **cohort analysis**.  
The objective is to understand how service usage, incidents, and revenue evolve over time for different user cohorts.

---

## 📂 Dataset Description

- **Source:** Data provided by Ironhack Payments  
- **Files used in the analysis:**  
  - `extract - cash request - data analyst.xlsx` → Cash advance requests  
  - `extract - fees - data analyst.xlsx` → Fees and revenue  
  - `Lexique - Data Analyst.xlsx` → Data dictionary  

- **Key aspects:**  
  - Cohorts are defined by the month of the first cash advance  
  - Some fields contain missing values  
  - Duplicate transactions exist and were cleaned  
  - Date formats were standardized for analysis  

---

## 🎯 Research Goal

Identify sales patterns by product line, time period, and geographical region, and uncover key factors influencing sales performance.

---

## 🛠 Steps Taken

1. **Data Cleaning**
   - Handled missing values in key columns
   - Reformatted date columns for consistency
   - Removed duplicates and irrelevant columns

2. **Exploratory Data Analysis (EDA)**
   - Summary statistics for sales and product lines
   - Grouped sales by month, quarter, and product category
   - Visualized trends with boxplots, bar charts, and line plots

3. **SQL Integration**
   - Queried dataset to answer business questions

---

## 📌 Main Findings

- **Seasonality:** Sales peak in Q4, likely due to holiday demand  
- **Top Performers:** Classic Cars consistently generate the highest revenue  
- **Regional Insight:** USA dominates sales volume, but EMEA excels in high-end products  
- **Deal Size:** Large deals cluster in specific product lines and regions  

---

## 💻 How to Reproduce

**Prerequisites:**
- Python **3.10+**
- Libraries: `pandas`, `matplotlib`, `seaborn`, `numpy`

**Run Instructions:**
1. **Clone this repository**
   ```bash
   git clone https://github.com/nataliadominguez99/Vehicles-Sales-Project.git

2. **Navigate to the project folder**
   ```bash
    cd Vehicles-Sales-Project

3. **Open the Jupyter Notebook**
- If you use Jupyter Notebook:
   ```bash
   jupyter notebook "Vehicles Sales Data Analysis.ipynb"
- Or, open it in VSCode by double-clicking the file or using:
   ```bash
    code "Vehicles Sales Data Analysis.ipynb"
  
4. **Ensure the dataset is in the correct location**
- The file sales_data_sample.csv must be in the same directory as the notebook.

5. Run all cells
- Select Cell > Run All in Jupyter Notebook or VSCode to reproduce the analysis.

## 🚀 Next Steps

- Build predictive models to forecast user retention and revenue  

---

## 📁 Repo Structure
```bash
├── Cohort Analysis - Ironhack payments Code.ipynb     # Jupyter Notebook with cleaning, EDA, cohort analysis
├── Cohort Analysis - Ironhack payments.pdf            # PDF report
├── extract - cash request.xlsx                        # Cash requests dataset
├── extract - fees.xlsx                                # Fees and revenue dataset
├── Lexique.xlsx                                       # Data dictionary
└── README.md                                          # Project documentation
