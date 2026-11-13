**Project summary**

Built an interactive Excel dashboard analysing diabetes risk across 15,000 patients. It shows KPIs (total patients, % high risk, average HbA1c, average BMI), how blood sugar, HbA1c and waist size change with age, stress and physical activity, and the BMI spread, all controlled by five slicers.

**Tools & Skills**

- **Tool:** Microsoft Excel (PivotTables, Slicers, PivotCharts, GETPIVOTDATA)
- **Data Type:** Structured patient health data (15,000 records, 19 fields including age, BMI, HbA1c, fasting blood sugar, stress level, physical activity and diabetes risk)
- **Data Preparation:** cleaned the raw data into a separate sheet used as the single source for all PivotTables
- **PivotTables:** summaries by age band, stress level, physical activity and BMI range, with averages and % of total
- **Dashboard Design:** KPI cards and linked charts (line, bar, column) controlled by slicers for City, Gender, Age, Physical Activity and Family History
- **KPI Analysis:** Total Patients, % High Risk, Average HbA1c, Average BMI
- **Dynamic Cards:** fixed the % High Risk card going blank under slicers by using GETPIVOTDATA with IFERROR instead of a fixed cell link
- 
- **Trend Analysis:**
  - **Age vs Fasting Blood Sugar:** Average fasting blood sugar goes up with every age band, from 148.6 (under 20) to 196.7 (age 70-80). *Conclusion: older patients need more regular sugar checks.*
  - **Stress vs HbA1c:** Average HbA1c rises from 6.6 (stress level 1-2) to 7.1 (stress level 9-10). *Conclusion: higher stress goes together with poorer long-term sugar control.*
  - **Physical Activity vs Waist Size:** Sedentary patients average 106.5 cm, Moderate 100.0 cm and Active 94.3 cm. *Conclusion: the more active a patient is, the smaller the waist.*
  - **BMI Spread:** Most patients (46.91%) are in the 20-25 BMI range, and only about 6% are above 30. *Conclusion: most patients have a normal BMI, so BMI alone does not explain the risk.*

- **Business Insights:**
  - 15% of all patients (2,250 of 15,000) are High risk.
  - Sedentary patients are the most at risk: 21.01% are High risk, compared with 14.36% of Moderate patients and 9.78% of Active patients. Sedentary patients are more than twice as likely to be High risk as Active patients.
  - Conclusion: the hospital should focus its screening and lifestyle programs on sedentary, older and high-stress patients, and promote physical activity as a simple way to lower diabetes risk.*
    <img width="1920" height="1020" alt="Diabetes Risk SS" src="https://github.com/user-attachments/assets/75199cb1-7e72-419d-a63f-431dda8dfd95" />
