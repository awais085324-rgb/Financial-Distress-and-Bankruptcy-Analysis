# Financial-Distress-and-Bankruptcy-Analysis
## 📌 The Project Mission
Why did I build this? To turn "Liquidity Panic" into a structured plan. Using a dataset of 6,800+ firms, I developed a multi-stage audit framework to identify the structural and operational precursors to bankruptcy before they become a reality.

## 🛠️ Stage 1: The Engine Room (Python)
Before any visuals were created, I used Python to perform a deep-dive statistical audit. I didn't want to guess which ratios mattered—I wanted the data to tell me.

**Libraries:** 
Pandas, NumPy, Seaborn, Matplotlib.

**Correlation Mapping:** Ran a correlation matrix across 95+ variables to pinpoint the "Smoking Guns"—specifically identifying ROA and Net Profit as the primary drivers of insolvency.

**Data Sanitization:** Automated the cleaning of complex financial headers and handled null values to ensure the data was "Power BI Ready."

## 📗 Stage 2: The Logic Check (Excel)
I used Excel as the "Ground Truth" to validate the data and build quick logic layers before the final visualization.

**Risk Categorization (IF Statements):** =IF(Quick_Ratio < 0.5, "Critical", IF(Quick_Ratio < 1.0, "Critical", "Healthy"))
**Insight:** This created the "Stability Score" used to filter high-risk firms.
**Data Consolidation (VLOOKUP):** =VLOOKUP(Firm_ID, Industry_Mapping!$A$2:$B$500, 2, FALSE)
F**inancial Aggregation (SUM/AVERAGE):** Utilized AVERAGE to determine industry norms for ROA, allowing for "Outlier Detection" of underperforming firms.

## 📊 Stage 3: The Executive Dashboard (Power BI)
The final stage was transforming raw analysis into a "Forest Audit" aesthetic dashboard—designed to make a decision in 30 seconds.

## 📈 Core Insights Summary
The Profitability Lead: Low ROA signals structural failure long before cash runs out.The 0.5 Liquidity Trap: A Quick Ratio below 0.5 is the "point of no return."

<img width="1919" height="995" alt="Screenshot 2026-05-12 124258" src="https://github.com/user-attachments/assets/eccd5943-5c58-438f-b05b-f38fab6a2b42" />
<img width="1197" height="954" alt="Screenshot 2026-05-12 124331" src="https://github.com/user-attachments/assets/467be625-6ed9-4f02-b0c1-f1bc0bc20093" />
<img width="1199" height="811" alt="Screenshot 2026-05-12 124444" src="https://github.com/user-attachments/assets/4634fb5c-f4d7-4c85-8ec4-8aeee16d0be9" />
<img width="1226" height="851" alt="Screenshot 2026-05-12 124412" src="https://github.com/user-attachments/assets/0d30b787-a66d-439e-9729-fb3f9381dde3" />
<img width="1200" height="852" alt="Screenshot 2026-05-12 124352" src="https://github.com/user-attachments/assets/5ae2f5b4-6283-4744-b0fc-51713abdcdf2" />
<img width="1912" height="982" alt="Screenshot 2026-05-12 124610" src="https://github.com/user-attachments/assets/fb01a494-682b-4c62-b9b6-b889a1bda80d" />





The Fragility Floor: High debt-to-asset ratios remove the safety net, making even small market dips fatal.
