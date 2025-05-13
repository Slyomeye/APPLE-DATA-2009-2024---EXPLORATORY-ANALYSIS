# APPLE-DATA-2009-2024---EXPLORATORY-ANALYSIS
I developed a project in power BI, Data collection, Data Cleaning, Data Analysis, Data Visualization
## Objective: Analyze Apple’s financial trends, profitability, operational efficiency and market valuation to inform strategic decision making
Dataset:[<a href = https://github.com/Slyomeye/APPLE-DATA-2009-2024---EXPLORATORY-ANALYSIS/blob/main/Apple%202009-2024.csv >Dataset</a>]
## Data Collection: I imported the dataset into power BI Desktop using “Get Data” and proceeded to transform the data using power Query Editor.
## Data Cleaning:
-	Checked for null values in all the key financial columns.
-	Removed duplicate values
-	Ensured data types are correctly set; decimal number data type for financial figures, whole number data type for Employee column.
-	Renamed columns for clarity and consistency.
-	Filtered out non relevant columns.
-	Converted PE ratio to percentage format.
## Key Metrics to Analyze:
-	KPI’s (Key Performance Indicators)
-	Growth trends: EBITDA (Earnings Before Interest, Tax Deductions and Amortization) and Revenue strength
-	Profitability for shareholders: Gross margin, Net Incomes and EPS (Earnings Per Share) 
-	Market valuation relative to earnings: PE ratio trends
-	Debt Ratio: determined by the total liabilities per the total Assets
-	Cash reserves, Asset utilization and employee productivity.
##Created DAX Measures to determine values.
-	Total Revenue = SUM (Revenue)
-	Total Net Income = SUM (Net Income)
-	Net Profit Margin = DIVIDE ([Total net income], [Total Revenue]) 
-	Total EBITDA = SUM (EBITDA)
-	EBITDA Margin = DIVIDE ([Total EBITDA], [Total Revenue])
-	Total Employee = SUM (Employee)
-	Revenue Per Employee = DIVIDE ([Total Revenue], [Total Employee])
-	Net Income Per Employee = DIVIDE ([Total Net Income], [Total Employee])
-	Average PE Ratio = AVERAGE (PE Ratio)
-	Average Year Close Price = AVERAGE (Year Close Price)
-	Total Cash on Hand = SUM (Cash on Hand)
-	Total Liabilities = SUM (Liabilities)
-	Total Assets = SUM (Assets)
-	Debt to Asset Ratio = DIVIDE ([Total Liabilities], [Total Assets])
-	Average EPS = AVERAGE (EPS)
-	Operating Margin = DIVIDE ([Total Operating income], [Total Revenue]) 
-	Equity = ([Total Assets] – [Total Liabilities])
 ##Dashboard:
-	Line charts: EBITDA, Net Profit Margin, PE Ratio trends over time
-	Scatter chart: Cash Vs Long Term Debt
-	Area Chart: Total Assets Vs Total Liabilities
-	Column Chart: Gross Margin Vs Operating Margin
-	KPI’s
-	Slicer: Year
##INSIGHTS
Profitability Margin
-	The net profit margin increased from 21% in 2020 to 25% in 2023 before a slight dip in 2024.
-	The EBITDA margin improved from 28% in 2020 to 34% in 2024 reflecting good operational strength.
Financial Check
-	Long term debt introduced in 2012 peaked at $109m in 2021 indicating a shift in financing strategy
-	The cash on hand is healthy but declining slightly and it could mean active investment or debt servicing.
-	The gross margin has been relatively stable, indicating good cost control, strong pricing power.
Employee Productivity
-	The revenue per employee grew from 1.87m in 2020 to 2.38m in 2024.
-	The net income per employee rose from 0.39m to 0.57m which indicates improved efficiency.
Market Performance
-	PE (Price to Earnings) Ratio peaked at 40 in 2024 meaning investor optimism or overvaluation risk.
-	The PE ratio fluctuates, suggesting varying market sentiments.

##RECOMMENDATIONS
-	Monitor debt levels closely, consider debt management strategies: long-term debts need to be reduced or avoided to improve the balance sheet health.
-	The leverage of employee efficiency with strategic hiring in respect to revenue growth to sustain productivity gains.
-	Enhancing of cash flow management especially as cash on hand is shrinking despite profits.
-	Communicating of margin growth and its efficiency gains clearly to investors to justify the high PE (Price to Earnings) valuation.
-	Preparation of possible PE correction if growth slows either to diversify the revenue or increase dividends to retain confidence of investors.
##CONCLUSION
Apple has demonstrated resilient growth and operational excellence, driven by innovation and strategic financial management. However, rising debt and market expectations require proactive measures like continued innovation and cost management for sustained growth.
