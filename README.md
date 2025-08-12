# **Bank Loan Report Dashboard – Summary Page**
📌 Overview
The Bank Loan Report is a Power BI project that provides a detailed view of a bank’s loan portfolio performance.
This Summary Page displays high-level KPIs, good vs. bad loan segmentation, loan status breakdown, and month-over-month (MoM) trends to assist in financial decision-making and risk assessment.

**Key Metrics**
Total Loan Applications: 38.6K (MoM: +6.9%)

Total Funded Amount: $435.8M (MoM: +13%)

Total Amount Received: $473.1M (MoM: +15.8%)

Average Interest Rate: 12.0% (MoM: +3.5%)

Average Debt-to-Income Ratio (DTI): 13.33% (MoM: +2.7%)

**Good vs. Bad Loan Analysis**
Good Loans (86.2%)

Applications: 33K

Funded Amount: $370.2M

Amount Received: $435.8M

Bad Loans (13.8%)

Applications: 5.3K

Funded Amount: $65.5M

Amount Received: $37M

Loan Status Breakdown
Loan Status	Applications	Funded Amount	Amount Received	MoM Funded Amt	MoM Apps Recv	Avg Interest
Current	1,098	$188.66M	$241.99M	37.61%	32.73%	15.1%
Charged Off	5,333	$65.53M	$37.28M	16.26%	33.30%	13.8%
Fully Paid	32,145	$351.36M	$411.59M	10.51%	12.72%	11.6%
Total	38,576	$435.78M	$473.07M	13.04%	15.84%	12.0%

Filters Available
Status: All, Current, Charged Off, Fully Paid

Grade: Loan grading system

Purpose: Education, Business, Personal, etc.

Insights
Strong portfolio quality with 86.2% good loans.

Charged-off loans account for $65.5M funded but only $37M received, indicating losses.

Fully paid loans dominate, ensuring steady repayments.

Interest rates are stable at ~12%, with slight monthly increase.

🛠 Tools & Technologies
Data Source: SQL Server (Loan Data)

Visualization: Power BI

Data Preparation: SQL Queries, Joins, Aggregations

**DAX Measures**

Good Loan % = Good Loan Applications ÷ Total Loan Applications

Bad Loan % = Bad Loan Applications ÷ Total Loan Applications

MoM % Change = (Current Month – Previous Month) ÷ Previous Month × 100

📂 Project Structure in GitHub
pgsql
Copy
Edit
/Bank-Loan-Report
   ├── Summary_Page.png
   ├── Overview_Page.png
   ├── Details_Page.png
   ├── README.md
   └── SQL_Queries.sql
