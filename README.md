# APPLE-DATA-2009-2024---EXPLORATORY-ANALYSIS
I developed a project in power BI, Data collection, Data Cleaning, Data Analysis, Data Visualization
## Objective: Analyze Apple’s financial trends, profitability, operational efficiency and market valuation to inform strategic decision making
Dataset:
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
