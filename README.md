# Bank Loan Summary Analysis using PowerBi
## Project: This project uses data from MS_SQL and Power BI desktop to help bank analyze the loans.

### Key Features:
1. Analyze and view total loan applications till date, amount received from the customers
2. Track good and bad loans, monthly trend, purpose of the loan granted.
3. Implementing filter parameters , page navigation , YTD, MTD KPI's.

### Solution Approach:
The following approach was used to implement the dashboard:

#### Data Import and Analysis :
The bank loan data was available in a csv file which was imported to MS-SQL server database. Initial insights were drawn from the data using SQL queries to gain a preliminary understanding of the loan transactions.

#### Connecting SQL to PowerBI :
The SQL database was connected to PowerBI and imported the dataset and tables into PowerBI.

#### Data Modeling and Relationship :
Additional Date table was added to the PowerBI model to analyze date related data such as YTD ,MTD and one to many relationship was established with the loan data.

#### Data Cleaning and Transformation:
PowerBI's transformation features like Column distribution , column quality were used to find dupicate , missing values in the data and missing values were replaced using appropriate techniques.

#### Dashboard Creation :
1. The first dashboard which was created was "Summary" to provide an overview of the bank data. This dashboard focused mainly on the high level metrics like YTD Total Applications, YTD Total Funded Amount, YTD Average DTI score etc ,MTD metrics and MoM change for each of the KPI's, pie charts to show the good loans vs bad loans issued ,cross tab for loan status.
2. The second tab included an overview for analysing the Monthly trend ,state wise trend, analysing the loan tenure, homeownership etc.
3. This included a detail summary of all the availbale loans.

### Conclusion:
The above dashboard helped in understanding the finance domain and harnessing different PowerBI features like data modeling, power query, time intelliegnce functions, advance DAX queries, filter functions, KPI's, navigations , charts like treemap, shape map.

