# Fitness-Club-Advanced-Excel-Analysis
# 🏋️‍♀️ PowerFit India - Fitness Club Analysis

Welcome to the **Advanced Excel Project** for **PowerFit India**!  
This analysis helps uncover key insights about member retention, revenue, referrals, and attendance behavior using Excel.

---

## 📁 Dataset Overview

- **Source**: Internal Club Membership Data
- **Total Rows**: 30+ members
- **Total Columns**: 11
- **Data Points**:
  - `Member_ID`, `Full_Name`, `Age`, `Gender`
  - `Start_Date`, `End_Date`, `Monthly_Fee`
  - `Membership_Type` (Basic, Standard, Premium, Family)
  - `City`, `Attendance`, `Referred_By`

---

## 🎯 Objectives

1. Calculate **membership duration** for each member.
2. Evaluate the **impact of referrals** on average fee.
3. Compute **revenue metrics** per member, segment, and city.
4. Identify **low-engagement members** for retention planning.
5. Build a **segment profitability dashboard**.
6. Analyze **gender & age distribution** across membership types.

---

## ✅ Tasks & Solutions

### 1️⃣ Membership Duration (in Months)
- Used Excel date formulas to calculate active months:
  ```excel
  =INT((End_Date - Start_Date)/30)

 2️⃣ Referral Impact
Created a new Referred column:

excel
Copy
Edit
=IF(ISBLANK(Referred_By), "No", "Yes")

 3️⃣ Revenue Calculation
Calculated Total_Revenue per member:

excel
Copy
Edit
=Monthly_Fee * Membership_Duration_Months

📊 Tools & Features Used
✅ PivotTables & PivotCharts

✅ Calculated Columns & Fields

✅ Slicers for interactive dashboards

✅ Conditional Formatting

✅ Excel formulas: IF, ISBLANK, INT, Date math

💡 Conclusion
This project helps PowerFit India understand its members, improve retention, and guide data-driven decisions for marketing and pricing.
