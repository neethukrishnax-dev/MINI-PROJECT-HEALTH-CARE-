Data Cleaning Using Power Query 
*Imported the healthcare dataset into Power Query.
*Created a separate cleaned Sheet named Solutions.
*Cleaned the Name column by removing unnecessary spaces and correcting capitalization.
*Cleaned the Billing Amount values and formatted them to two decimal place
*Verified the Date of Admission column and its data type
The cleaned Solutions data was imported into Power BI for analysis
DAX Measure – Total Patients
Total Patients = COUNTROWS(Solutions)
DAX Measure – Total Billing Amount
Total Billing Amount = SUM(Solutions[Billing Amount])
Seven main visualizations were created 
Card,Bar Chart,Donut Chart, Column Chart,Line Chart,Scatter Chart
A final Healthcare Data Analysis Dashboard was created in Power BI 
