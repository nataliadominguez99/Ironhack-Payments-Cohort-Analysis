# 📊 Ironhack Payments Cohort Analysis

This project analyzes the behavior of users and financial metrics of **Ironhack Payments’ cash advance service** through a **cohort analysis**.  
The objective is to understand how service usage, incidents, and revenue evolve over time for different user cohorts.

---

## 📂 Dataset

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

### Data Cleaning
- Handled missing values and duplicates  
- Standardized date formats  
- Removed irrelevant columns  

### Exploratory Data Analysis (EDA)
- Descriptive statistics for users, requests, and fees  
- Visualizations (line plots, bar charts, heatmaps)  
- Detection of anomalies and patterns  

### Cohort Analysis
- Cohorts defined by first cash advance month  
- Metrics computed per cohort and tracked over time  

### Visualization
- Cohort tables and charts   

---

## 📌 Main Findings

- Service usage decreases after the first months for most cohorts  
- Some cohorts show higher incident rates  
- Early cohorts generate higher total revenue  
- Retention metric highlights user loyalty differences  

---

## 💻 How to Reproduce

**Requirements:**  
- Python 3.10+  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`

**Run Instructions:**  

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/ironhack-payments-cohort-analysis.git

# 2. Navigate to the folder
cd ironhack-payments-cohort-analysis

# 3. Open the notebook
jupyter notebook "ironhack_payments.ipynb"

---

## 📁 Repo Structure
```bash
├── ironhack_payments.ipynb                 # Jupyter Notebook with cleaning, EDA, cohort analysis
├── extract - cash request - data analyst.xlsx   # Cash requests dataset
├── extract - fees - data analyst.xlsx           # Fees and revenue dataset
├── Lexique - Data Analyst.xlsx                  # Data dictionary
├── Tableau Dashboard/                           # Tableau visualizations
├── Data Quality and EDA Report.pdf              # Data quality and EDA report
├── requirements.txt                             # Python dependencies
└── README.md                                    # Project documentation
