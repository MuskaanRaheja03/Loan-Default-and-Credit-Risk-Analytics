# 📊 Loan Default and Credit Risk Analytics Pipeline

This project presents an end-to-end credit risk analytics framework combining data preprocessing, risk segmentation, machine learning evaluation, and interactive dashboarding to support data-driven lending decisions.

The solution analyzes loan issuance and default trends (2007–2018) across borrower risk categories and loan purposes to identify high-risk segments, evaluate default concentration, and improve decision transparency.

---

## 🎯 Project Objective

To design a structured credit risk monitoring system that:

- Segments borrowers by **FICO and DTI risk bands**
- Quantifies default concentration by **loan purpose**
- Tracks portfolio performance over time
- Supports threshold-based risk mitigation strategies
- Enables evidence-based decision support for lending institutions

---

## 🔬 Analytical Workflow

The project follows a structured analytics pipeline:

### 1️⃣ Data Preparation
- Data cleaning and validation  
- Handling missing values  
- Risk band categorization (FICO & DTI segmentation)  

### 2️⃣ Feature Engineering
- Default rate computation by risk band  
- Loan bucket categorization  
- Aggregated KPI generation  
- Temporal trend structuring (year-wise analysis)  

### 3️⃣ Risk Evaluation
- Precision–Recall trade-off analysis  
- Threshold sensitivity analysis  
- Risk band impact assessment  

### 4️⃣ Visualization & Decision Support
- KPI dashboard modeling (Power BI)  
- Interactive filtering (Risk Band, Loan Purpose, Year)  
- Portfolio-level performance monitoring  

---

## 📊 Dashboard Overview

**Time Frame:** 2007 – 2018  
**Total Loans Analyzed:** ~1,000,000  
**Total Defaulted Loans:** ~269,000  
**Average FICO Score:** ~698  

### Key Dashboard Features

- Risk segmentation by **FICO band**  
- Default rate analysis by **DTI band**  
- Loan purpose concentration analysis  
- Year-over-year default trend tracking  
- Portfolio KPIs for strategic monitoring  

> ⚠️ Note: `.pbix` files cannot be previewed in GitHub. Download locally and open in Power BI Desktop for full interactivity.

---

## 🔎 Key Insights

- Borrowers with **FICO scores below 650** exhibit significantly higher default rates.  
- Certain loan purposes (e.g., debt consolidation) contribute disproportionately to default volume.  
- Default rates peaked mid-period before stabilizing.  
- Risk band segmentation improves early identification of vulnerable borrower groups.  
- Threshold tuning significantly impacts recall vs precision trade-offs in default prediction.  

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `credit-risk-dashboard.pbix` | Interactive Power BI dashboard |
| `dashboard_preview.jpeg` | Static preview of the dashboard |
| `End-to-End Credit Risk Analytics Pipeline.ipynb` | Machine learning workflow and evaluation |
| `README.md` | Project documentation |

---

## 🛠️ Tools & Technologies

- Python (Data preprocessing & modeling)  
- Power BI (Dashboard & visualization)  
- Pandas / NumPy (Data manipulation)  
- Scikit-learn (Model evaluation)  
- Risk segmentation framework (FICO & DTI banding)  

---

## 🔐 Data & Ethics

This dataset was used strictly for academic and portfolio demonstration purposes.

- No personally identifiable information (PII) was used.  
- The analysis is intended for educational and decision-support modeling demonstrations.  
- Results should not be interpreted as financial advice.  

---

## 📚 Data Source

Panuganti, Manasa. (2025).  
*Open Science Workflow for Loan & Credit Card Default Prediction (v1.0).*  
Zenodo.  
https://doi.org/10.5281/zenodo.16804306  

---

## 👩‍💻 Author

**Muskaan Raheja**  
B.Sc. Computer Science – Carleton University  
GitHub: https://github.com/MuskaanRaheja03  
