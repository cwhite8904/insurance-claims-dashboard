# insurance-claims-dashboard
Power BI Dashboard for Insurance Claims Analysis
## 🔍 Objective
Analyze health-related insurance claims data to uncover patterns, risk factors, and trends that influence claim amounts — including BMI, smoker status, and region.

---

## 📁 Dataset
- 1,340 synthetic insurance claim records
- Key features: Age, Gender, BMI, Blood Pressure, Diabetic, Smoker, Children, Region, Claim Amount

---

## 🧹 Data Preparation
- Cleaned missing values
- Renamed columns for clarity
- Created new DAX columns:
  - `AgeGroup`
  - `BMI_Category`
- Added a simulated `ClaimDate`
- Built a `DateTable` for time-based visuals

---

## 📊 Dashboard Features
- **KPI Cards**: Total Claims, Avg Claim, Total Patients
- **Visuals**:
  - Claims by Region, BMI, Age Group
  - Pie Chart: Smoker Status
  - Line Chart: Claims Over Time
  - Stacked Comparison: Smokers vs Non-Smokers
- **Slicers**:
  - Gender, Diabetic, Region, AgeGroup, ClaimDate

---

## 💡 Insights
- Smokers had higher average claims
- Obese individuals had more expensive claims
- Southeast region filed the most claims
- Adults (30–49) were the most frequent claimants

---

## 🛠 Tools Used
- Power BI Desktop
- DAX for calculated fields and measures
- Power Query for transformation
- Power BI Service (for publishing)

---

## 📎 Files
- `Insurance_Claims_Dashboard.pbix` - Main Power BI file
- `Insurance_Claims_Report.pdf` - Exported dashboard (optional)

---

## 🔗 Live Demo (if published)
[View Public Report on Power BI Service](#)

---

## 🧠 Author
**[Your Name]**  
Aspiring BI Developer | MBA in AI & Business Analytics  
[LinkedIn](https://www.linkedin.com/in/your-profile) | [Portfolio](#)
