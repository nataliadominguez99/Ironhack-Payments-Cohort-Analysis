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

The cohort analysis tracks:  

- **Service Usage Frequency** – how often users from each cohort request cash advances over time  
- **Incident Rate** – incidents per cohort  
- **Revenue** – financial performance per cohort  
- **Additional Metric** – retention / user behavior measure

---

## 🛠 Steps Taken

1. **Data Cleaning**
   - Handled missing values in key columns
   - Reformatted date columns for consistency
   - Removed duplicates and irrelevant columns

2. **Exploratory Data Analysis (EDA)**
   - Descriptive statistics for users, requests, and fees  
  - Visualizations (line plots, bar charts, heatmaps)  
  - Detection of anomalies and patterns 

3. **Cohort Analysis**
   - Cohorts defined by first cash advance month
   - Metrics computed per cohort and tracked over time

4. **Visualization**
- Cohort tables and charts  
- Tableau dashboard

---

## 📌 Main Findings

- Service usage decreases after the first months for most cohorts  
- Some cohorts show higher incident rates  
- Early cohorts generate higher total revenue  
- Retention metric highlights user loyalty differences  

---

## 💻 How to Reproduce

**Prerequisites:**
- Python **3.10+**
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`

**Run Instructions:**
1. **Clone the repository**
  ```bash
  git clone https://github.com/yourusername/ironhack-payments-cohort-analysis.git

2. **Navigate to the project folder**
   ```bash
    cd ironhack-payments-cohort-analysis

3. **Open the Jupyter Notebook**
- If you use Jupyter Notebook:
   ```bash
   jupyter notebook "ironhack_payments.ipynb"
- Or, open it in VSCode by double-clicking the file or using:
   ```bash
    code "ironhack_payments.ipynb"
  
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
