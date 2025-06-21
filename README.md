# hospital-readmission-analytics
A data analysis project using excel to explore hospital readmission patterns, cost breakdowns, and risk indicators.
# Hospital Readmissions Analysis (Excel Project)

This project analyzes synthetic hospital data to identify patterns in readmissions, average cost per department, and patient risk groups using Excel.

## 📊 Tools Used
- Microsoft Excel
- PivotTables & Charts
- Formulas (IF, COUNTIFS, AVERAGE, etc.)

## 🧼 Data Cleaning Summary
- Removed duplicate entries
- Created Length of Stay, Age Groups, and Total Cost per Patient
- Handled blanks in 'Readmitted?' column

## 💡 Key Insights
- Neurology had the highest readmission count and second-highest cost
  - Suggests need for post-discharge follow-up.
- Cardiology had the lowest readmission volume but the highest cost per patient
  - Oppurtunity to manage high-cost acute cases.
- 70+ age group had the highest readmissions (~30%)
- Unexpectedly, non-readmitted patients had slightly higher average costs than those readmitted — suggesting further analysis needed

## 📈 Dashboard Preview
- ![Hospital Readmission Dashboard](https://github.com/OmarKanu96/hospital-readmission-analytics/raw/main/Hospital_Readmissions_Synthetic_Data%20(2).pdf)

## 📁 Files Included
- [View Excel Dashboard](https://1drv.ms/x/c/c8d5dcf9822e7dff/ESKfbhmXhrhNmWvMrI_ipsEBCe4pv4xdHRIgY1sThub9Ow?e=fLSLzI)
- [Synthetic dataset (for reproducibility)](https://1drv.ms/x/c/c8d5dcf9822e7dff/ESKfbhmXhrhNmWvMrI_ipsEBCe4pv4xdHRIgY1sThub9Ow?e=lRxi7L)

---

## 🚀 Next Steps / Recommendations

- **Implement follow-up protocols in high-risk departments (Neurology)**
  - Focus on reducing readmission volume
  - Monitor post-discharge outcomes using week-long check-ins

- **Conduct total patient-level cost analysis**
  - Combine multi-visit data to fully assess cost impact of readmissions

- **Explore predictive modeling**
  - Use discharge data to flag high-risk patients before they leave

- **Design age-specific interventions**
  - Seniors (70+) have highest readmission volume
  - Aim to reduce their rate by 10% within 6 months via remote check-ins

- **Build department-level dashboards**
  - Create visuals for Neurology and Cardiology teams to monitor KPIs in real time

- **Integrate additional data sources**
  - Bring in EMR or insurance claim data for deeper segmentation and forecasting
