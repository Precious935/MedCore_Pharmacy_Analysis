# 🏥 MedCore Pharmacy — Management Performance Dashboard (Jan–Sep 2026)

An interactive, one-page executive Excel dashboard built for **Dr. Balogun** and the Operations Management team to track revenue performance, profit margins, product demand, and customer purchasing behavior across **Ikeja, Lekki, and Yaba** branches.

![MedCore Pharmacy Dashboard Preview](dashboard_preview.png)

---

## 📌 Business Objectives
1. **Executive KPIs:** Track Total Revenue (`₦5,306,580`), Gross Margin (`24.7%`), Total Sales (`1,065`), Average Sale Value (`₦4,983`), and Target Attainment (`98.3%`).
2. **Goal Variance Tracking:** Identify monthly revenue trends against branch targets and spotlight months that missed goals.
3. **Branch & Category Breakdown:** Compare revenue generation across branches and 8 therapeutic drug categories.
4. **Product & Seasonal Insights:** Highlight top-performing medications and analyze the rainy-season surge in antimalarial demand.
5. **Channel & Payment Mix:** Understand how customers order (`Walk-in`, `Prescription`, `Delivery`) and pay (`Cash`, `Bank Transfer`, `POS`, `HMO`, `NHIA`).

---

## 🔍 Key Insights & Findings
* **Target Performance:** Achieved **98.3% of the ₦5.40M target**, with **4 months missing target** (January, February, April, and September).
* **Top Branch:** **Lekki** leads branch revenue at `₦1,893,530`, followed by **Yaba** (`₦1,741,890`) and **Ikeja** (`₦1,671,160`).
* **Rainy-Season Surge:** Antimalarial demand spiked sharply in **May (`₦241,690`)** and **July (`₦213,560`)**, making *Artemether/Lumefantrine 80/480mg (x6)* the #1 revenue-generating drug (`₦1,277,380`).
* **Customer Behavior:** **Walk-in** customers account for **62%** of revenue, while **Cash** and **Bank Transfer** remain the dominant payment methods.

---

## 🛠️ Technical Highlights (Excel)
* **Data Modeling & Aggregation:** Built 8 dynamic PivotTables on a dedicated `CALC` workspace linked to `tblSales` (1,065 records).
* **Dynamic Conditional Combo Chart:** Engineered `IF` and `NA()` helper formulas to dynamically recolor monthly revenue bars (Teal for *Target Met*, Crimson for *Target Missed*) whenever Branch or Month slicers are toggled.
* **Interactive Slicers:** Connected custom-styled **Branch** and **Month** slicers across all KPI cards and visuals.

---

## 🚀 How to Use
1. Download [`MedCore_Pharmacy_Dashboard.xlsx`](MedCore_Pharmacy_Dashboard.xlsx).
2. Open in Microsoft Excel and enable macros/editing if prompted.
3. Use the **Branch** and **Month** slicers in the top-right corner to filter all visuals dynamically.
