# 🏦 Bank Client, Loan & Recovery Analytics — Tableau

An end-to-end Tableau dashboard project designed to analyze **client demographics, loan issuance patterns,** and **recovery performance**.
This project features **three fully interactive dashboard pages**, advanced **KPIs, slicers, dual-axis visuals,** and **navigation buttons** for seamless user experience.

---

## 📁 Project Structure

```
/Bank-Analytics
│
├── Tableau_BankAnalytics.twbx
├── /dataset
│     └── Bank Data Analytics.xlsx
└── /dashboardImages
       ├── Tableau_Dashboard_01.png
       ├── Tableau_Dashboard_02.png
       └── Tableau_Dashboard_03.png

```
---

# 📊 Tableau Dashboard
This Tableau workbook contains **3 analytical pages**:

1. BANK CLIENT ANALYSIS
2. LOAN & DISBURSEMENT ANALYSIS
3. RISK & RECOVERY INSIGHTS

Each page includes KPIs, advanced charts, filters, and navigation buttons for easy movement across the dashboards.

## **📌 1. Client Page — BANK CLIENT ANALYSIS**
🔘 Navigation Buttons
- Loan → Navigates to **LOAN & DISBURSEMENT ANALYSIS**
- Recovery → Navigates to **RISK & RECOVERY INSIGHTS**
  
### **🔹 KPIs**
- **Clients:** Total unique clients
- **Active Clients:** Clients with active loan accounts
- **Avg Loan Per Client:** Average loan amount per client
- **Top City:** City with highest active clients

### **🔹 Visualizations**
- **Heatmap Chart:** Top 5 Cities – Client Count by Loan Duration
- **TreeMap Chart:** Clients by Caste
- **Donut Chart:** Client Verification Status
- **Bar Chart:** Clients by Age Group
- **Line Chart:** Monthly Client Acquisition Trend

### **🔹 Slicers**
- Gender: *Male, Female*
- Religion: *Christian, Hindu, Muslim, Sikh, UNKNOWN*
- Year (Disburse Date): *2016, 2017, 2018, 2019, 2020*
- Quarter (Disburse Date): *Q1, Q2, Q3, Q4*

---

## **📌 2. Loan Page — LOAN & DISBURSEMENT ANALYSIS**
🔘 Navigation Buttons
- Client → Navigates to **BANK CLIENT ANALYSIS**
- Recovery → Navigates to **RISK & RECOVERY INSIGHTS**

### **🔹 KPIs**
- **Loan Amount:** Total approved loan amount
- **Default Loan Accounts:** Defaulted client accounts
- **Funded Loan Amount:** Amount actually disbursed
- **Loan Approval Rate:** Ratio of funded vs. applied loan

### **🔹 Visualizations**
- **Bar Chart:** Top 5 Loan Purpose Categories by Loan Amount
- **Bubble Chart:** Top 5 Loan Statuses by Client Accounts
- **Area Chart:** Loan Disbursement Trend Over Years
- **Combo Chart:** Monthly Funded Amount vs. Client Growth
- **Column Chart:** Top 5 States by Funded Loan Amount

### **🔹 Slicers**
- Year (Disburse Date): *2016, 2017, 2018, 2019, 2020*
- Month (Disburse Date): *January, February, March, April, May, June, July, August, September, October, November, December*
- Quarter (Disburse Date): *Q1, Q2, Q3, Q4*

---

## **📌 3. Recovery Page — RISK & RECOVERY INSIGHTS**
🔘 Navigation Buttons
- Client → Navigates to **BANK CLIENT ANALYSIS**
- Recovery → Navigates to **LOAN & DISBURSEMENT ANALYSIS**

### **🔹 KPIs**
- **Loan Fully Recovered:** Loans where total received > funded amount
- **High Risk Loan:** Delinquent or defaulted loans
- **Recovery Rate:** Total recovery / total loan amount
- **Total Recovery:** Sum of all recovered principal + interest

### **🔹 Visualizations**
- **Bar Chart:** Top 10 Branch by Delinquent Loan Count
- **Line Chart:** Recoveries Over Years
- **Donut Chart:** Default Loan Status
- **Stacked Column Chart:** Loan Recovery By Loan Term & Grade

### **🔹 Slicers**
- Year (Disburse Date): *2016, 2017, 2018, 2019, 2020*
- Month (Disburse Date): *January, February, March, April, May, June, July, August, September, October, November, December*
- Quarter (Disburse Date): *Q1, Q2, Q3, Q4*
- Loan Term: *36 months, 60 months*

---

# 📌 Features Included
- Multi-page navigation
- KPI cards with FIXED LOD calculations
- Heatmap, Donut, Treemap, Combo charts, Dual-axis visuals
- Dynamic slicers for demographic & loan attributes
- Top-N analysis
- Year/Quarter/Month time intelligence

---

# 🚀 How to Use This Project
1. Download the **.twbx** file
2. Open in **Tableau Public**
3. Go through the interactive dashboards with filters & navigation buttons

---

# 👩‍💻 Author  
**Aditi**  
Certified Data Analyst skilled in Excel, SQL, Power BI, Tableau & Data Visualization.

---

# ⭐ If You Like This Project
Please **star ⭐ the repository** — it motivates me to build more!

