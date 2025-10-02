PROJECT OBJECTIVE:
Analyze financial transaction data to uncover patterns, detect errors, assess customer behavior, and evaluate regional performance for better risk management and business decisions.
<br>
<br>
DATASET:<br>
<a href="https://github.com/sherinstella/Finance-Transaction-Analysis/blob/main/Merchant_table.csv">Mechant Data</a><br>
<a href="https://github.com/sherinstella/Finance-Transaction-Analysis/blob/main/cards_data.csv">Card Data</a><br>
<a href="https://github.com/sherinstella/Finance-Transaction-Analysis/blob/main/users_data.csv">Users Data</a><br>
NOTE:Transaction dataset not uploaded due to large file size, but dashboards and documentation are provided for reference.
<br>
<br>
DASHBOARD:<br>
<a href="https://github.com/sherinstella/Finance-Transaction-Analysis/blob/main/Screenshot%202025-10-02%20094918.png">Executive Dashboard</a><br>

<a href="https://github.com/sherinstella/Finance-Transaction-Analysis/blob/main/Screenshot%202025-10-02%20095041.png"> Regional Transactions</a><br>


<br>
<br>

PROCESS:<br>
Data Cleaning: Handled nulls, formatted dates, mapped MCC codes.<br>
Modeling: Star schema with transactions_data as fact; related to users, cards, MCC, cities, and states.<br>
KPIs Created: Total Transactions, Avg Amount, Credit Utilization, DTI Ratio, Errors, etc.<br>
Dashboards:<br>
1)Executive: KPIs, MCC trends, transaction types, error tracking.<br>
2)Regional: State/city-level insights, map visuals, online vs. physical trends.<br>
<br>
<br>

QUESTION KPI'S:<br>
What’s the total transaction volume and average amount?<br>
Which MCC categories and card types lead?<br>
How many errors occur and where?<br>
How does DTI ratio impact credit risk?<br>
Which regions and cities contribute most?<br>
What’s the gender-wise utilization?<br>
<br>
<br>
INSIGHTS:<br>
₹571M+ across 13M transactions; swipe most common.<br>
Money transfer & grocery stores top MCCs.<br>
211K transaction errors — concentrated by merchant.<br>
DTI Ratio of 139% signals credit risk.<br>
California & Texas lead in transaction value.<br>
Online transactions dominate city-level volumes.<br>
<br>
<br>

CONCLUSION:<br>
The dashboards provide a high-level and regional view of financial performance, helping teams improve fraud detection, credit strategy, and customer engagement through actionable insights.
