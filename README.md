# 🛡️ KYC Anomaly Detection Dashboard — Power BI + Python

Ever had a vendor onboarded without PAN, Aadhaar, or GSTIN — and realized it too late?

This project simulates a real-world compliance use case using a **KYC Anomaly Detection Dashboard** built in **Power BI**, powered by Python-generated data. The goal is to help organizations in **FinTech, RegTech, eCommerce, and Procurement** proactively identify and monitor high-risk vendors.

---

## 📌 Project Highlights

- **Built Using**: Power BI, Python (Faker, Seaborn, Pandas)
- **Dataset**: 2,000 synthetic vendor profiles (no real data used)
- **Use Case**: Simulate how internal audit or risk teams detect anomalies in vendor KYC compliance
- **Insights Delivered**:
  - Missing documentation (PAN, GSTIN, Aadhaar, Email, Phone)
  - Suspicious Txn-to-Billing ratios
  - High-risk document statuses (Pending, Incomplete)
  - Anomaly flags for account behavior

---

## 📊 Dashboard Features

### 📄 Page 1: KYC Overview
- **KPI Cards**: Total Vendors, Anomaly %, Average Billing, Submission Completion Rate
- **Violin Plot**: Document Submission Status vs Missing Fields
- **Scatter Plot**: Monthly Billed vs Invoiced (flagged by anomaly)
- **Column Chart**: Missing Field Distribution (0–3+)
- **Treemap**: Vendor City Distribution
- **Slicers**: Business Type, Document Status, Anomaly Flag, City

### 🕵️‍♂️ Page 2: Vendor Investigation
- **Table View**: Filterable table by city, anomaly, and document status
- **New Visual**: Violin plot, city-based breakdown removed for generalization
- **Interactive Filters**: Drilldown by risk category or anomaly behavior

---

## 🧠 Key Insights

- 🔴 22% of vendors flagged as anomalies due to documentation or activity risk
- 🟠 Txn-to-Billing Ratio > 0.01 highlighted 70+ vendors with suspicious behavior
- 🔵 Business Types like “Sole Proprietor” were 3x more likely to have missing documents
- 🟢 Email and phone are most commonly present, PAN is the most missing

---

## 🛠️ Tech Stack

| Tool         | Purpose                     |
|--------------|------------------------------|
| Power BI     | Dashboard UI + DAX Logic     |
| Python       | Data Simulation (Faker)      |
| Pandas       | Feature Engineering          |
| Seaborn      | Violin/Scatter Visualization |
| Power BI Slicers | Dynamic Filtering        |

---

## ✅ Installation & Usage

1. Clone this repository
2. Open Power BI Desktop
3. Connect to the `Python Script` as a data source (no CSV used)
4. Load visuals and adjust slicers
5. Customize filters or thresholds in DAX or Python for further exploration

---

## 💡 Why This Matters

Vendor onboarding risk is real — and compliance misses can cost millions. This project demonstrates how a BI analyst or product team can **simulate real-world regulatory workflows** using modern tools to surface anomalies before they impact the business.

---

## 📬 Contact & Collaboration

If you're in **compliance, BI, finance ops, or procurement tools**, let’s connect! I’m open to:
- Walkthroughs & live demos
- Integration ideas
- Production-grade adaptations

📫 Connect on [LinkedIn](https://www.linkedin.com/in/mayank-chaturvedi-91757a1a6/)  
📧 Email: mayankchaturvedi9636@gmail.com

---

## 🔖 Hashtags (for visibility & inspiration)
#powerbi #python #datavisualization #dashboarddesign #businessintelligence #pythonvisuals #dataengineering #seaborn #fakerlibrary #analyticsdashboard #kyc #riskanalytics #regtech #frauddetection #complianceanalytics #audittech #vendorcompliance #aml #riskmanagement #governancedata #dataanalytics #dataforgood #datasolutions #dataquality #dataprojects #machinelearning #aiinfinance #appliedai #advancedanalytics #bigdataanalytics #analyticsjobs #openforwork #portfolio #buildinpublic #careerinanalytics #jobsearch #freelancer #resumebooster #projectbasedlearning #careertransition #fintech #ecommerceanalytics #procurementanalytics #financialanalytics #supplychainanalytics #bfsisector #vendorrisk #internalaudit #financeops #datainnovation #analyst #flipkart #oyo #ola #boeing #marketing #marketinganalytics #digitalmarketinginsights #conversionoptimization #productanalytics #userjourney #lookerstudio #ga4 #googleanalytics #sql #postgresql #tableau #gurugram #genai #ai #budget #analysis #campaignperformance #productmanagement #programmanagement #funnelanalysis #marketingdashboard #datadriven #reporting #marketingstrategy #dashboard



![vendor_kyc_dashboard_page-0001](https://github.com/user-attachments/assets/0ff81218-94c5-4327-b979-50e90c569fc6)
![vendor_kyc_dashboard_page-0002](https://github.com/user-attachments/assets/83c0e725-e183-41ce-a898-44fdf0fa531f)


