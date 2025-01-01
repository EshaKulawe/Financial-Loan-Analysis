# Financial-Loan-Analysis

The objective of this project is to uncover actionable insights in the form of key loan-related metrics, their changes over time, and borrower behavior trends. Since banks face significant risks associated with loan defaults which can adversely impact profitability and long-term sustainability, the analysis also determines the underlying factors driving defaults and analyzes the patterns. This analysis helps financial institutions make data-driven decisions, improve risk management practices, and continuously track the health of their loan portfolios.
### Tools
- SQL: Used to find the key loan metrics as well as month-over-month growth parameters. It is also used to verify results found using Power BI.
- Power BI: The visualization tool was needed to explore data further and create charts and visualizations to come up with an Executive Summary Report and Detail Report.

### Data Cleaning
Power BI Query was used to clean the dataset. Checked the duplicates, handled the missing values, and corrected the discrepancies in the data.

### Power BI Reports
![image](https://github.com/user-attachments/assets/770b3054-6355-44ba-9e10-6f186382e230)
![image](https://github.com/user-attachments/assets/27c9c76e-a952-4279-8f97-9bbc5aa8be6f)

### EDA
- Total loan principal disbursed, total loan repayments, and total number of applications are showing consistent month-on-month increases for the year 2021.
- Almost 50% of the disbursed loans were given out for debt consolidation purposes.
- Loans with higher interest rates (above 13%) showed a significant increase in default rates compared to those with lower rates.
- Higher DTI slightly correlates with a greater likelihood of bad loans.
- Higher grades (e.g., A, B) have lower bad loan rates compared to lower grades (e.g., D, E, F).
- Approximately 37% loans are in the category of long-term loans (60 months). There is a high chance of defaults here, as the average interest rate and debt-to-income ratio are quite high.

### Strategy Recommendations
- Encourage shorter repayment terms to reduce the risk of long-term defaults.
- Offer flexible installment plans aligned with borrowers’ income schedules.
- Implement systems to flag accounts with early signs of delinquency (e.g., missed payments or credit utilization spikes).
- Restrict lending for lower grades (D, E, F) or charge higher rates to offset the risk.


