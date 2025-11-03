<h1>Health Care Evaluation (overview) </h1>

 Data Types: Mix of categorical, numerical, and date data

 Key fields:
- Patient demographics: Name, Age, Gender, Blood Type
- Medical info: Medical Condition, Medication, Test Results
- Operational data: Doctor, Hospital, Room Number, Admission Type, Date of Admission, Discharge Date,
- Financial data: Billing Amount, Insurance Provider

I have ensured dates are usable for time analysis and calculate the length of stay, a critical hospital metric. Used print(df.columns.tolist) to chech the spelling a spacing. This serves to clean and prepare my dataset. The average billing amountby medical condition has been expressed by a bar chat which shows all conditions are above $25000. The boxplot shows most common admission is the emergency, urgent and elective respectively. It compares the admission types and reveals workflow. Likewise maybe used to assume the department that yields the highest revenue for doctors. 

Using a linear regression model to identify which variables influence hostpital  billing the most (predictive analysis), the chart shows that gender has the highest influence on billing and medical condition with test results and admission type having little affect on billing amount.The line chart shows admissions by month. This allows us to assume the seasonal trends, currently at month 7 and 8 with the highest visits. 

 Business insight dashboard - 
This file can feed a dashboard showing KPIs like average billing, average lenght of stay and admissions by conditions 



