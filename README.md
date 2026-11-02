# 🚗 Fleet Operations & Compliance Analytics Dashboard

## 📌 Executive Summary
An automated, multi-tab Microsoft Excel analytics solution designed to audit driver gas allowances, track vehicle onboarding compliance, manage operational CRM records, and provide executive-level reporting. 

Built to handle high-volume operational raw data, this model reconciles financial variances between driver allowances ($28,000.00) and actual fuel spend ($108,467.07), while managing compliance tracking across 400 vehicle document records.

---

## 📊 Key Features & Functionality

### 1. Financial & Allowance Auditing (`Fleet_Analytics`)
* **Variance Analysis**: Reconciles individual driver monthly gas allowances against raw fuel transaction data.
* **Dynamic Lookups**: Utilizes `XLOOKUP` and `SUMIFS` formulas to aggregate total spend per driver dynamically.
* **Executive Callout**: Includes an integrated executive summary callout block highlighting core financial and operational findings.

### 2. Vehicle Document Compliance Tracker (`Compliance_Tracker`)
* **Record Auditing**: Tracks submission status across 400 vehicle onboarding records.
* **Dynamic KPI Summaries**: Implements `COUNTIF` formulas to tabulate submitted (370) vs. missing (30) documents.
* **Data Visualization**: Embedded executive doughnut/pie chart illustrating a **92.5% compliance rate**.

### 3. Integrated Data Architecture
* Built across 8 structured, relational tabs: `Fleet_Analytics`, `Compliance_Tracker`, `Drivers`, `Vehicles`, `Documents`, `Fuel_Raw`, `Service`, and `CRM`.

---

## 🛠️ Technical Stack & Formulas Used
* **Software**: Microsoft Excel (Advanced Data Modeling & Reporting)
* **Formulas**: `XLOOKUP`, `SUMIFS`, `COUNTIF`, `SUM`, `IF`
* **Features**: Dynamic KPI Blocks, Text Wrapping/Cell Formatting, Data Visualization Charts

---

## 🚀 How to Use
1. Download or clone the `Fleet_Operations_Dashboard.xlsx` file.
2. Open in Microsoft Excel 2016 or newer.
3. Navigate between `Fleet_Analytics` for financial variances and `Compliance_Tracker` for document audit status.
