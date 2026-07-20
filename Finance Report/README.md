### Finance Report

# Description
  Finance Report – an interactive report designed to democratize finance information for analysts, cfo and other departments. As a Power BI solution, it serves as a single, official source of data for all members of the organization. The report presents the groups and accounts of the Polish manufacturing company in 2016-2018.

# Tech Stack
  Power BI Desktop - main tool for report creation
  
  Power Query - data transformation
  
  Excel - raw data, and frameworks for data model
  
  Tabular Editor - mass creation of measures and calculation groups

  Power Point - front end layer

  Python script (in Power BI) - implementation of IBCS styled variance analysis for Balance Sheet

# Data Source
  The data comes from the financial statements of a Polish industrial company for the years 2016-2018. I received the data as part of a course assignment during my studies. The company requests that its name not be disclosed. The data was presented by year. To demonstrate the potential possibilities of the report, I manually split it equally across all months and manually set today's date as September 2017 to display both time flags referring to the future and the past. The data was provided to me in a flat Excel file.

# Features and Higlights

Business Problem:
  Different definitions of Finance KPIs across departments, lack of time consistency in reporting, and difficulty ensuring only authorized individuals have access to information.

Business Impact:
  In addition to solving the above problems with data unification, constant refresh time and access, the report offers additional options:

  Variance analysis for the previous year and the previous period - Built-in difference columns reduce analysis time and eliminate the need to manually calculate growth or decline for individual groups and accounts. This allows you to quickly identify strengths and weaknesses in your financial structure, both short-term and long-term. This applies to actual data, forecasts, and the entire year.

  Time Periods - The formatted table does not have months in columns in its structure as is often the case, instead the analyst can select the most frequently viewed time periods, such as: YTD, Last Year, Current Year, Forecast, Quarters and Trailing Months.
This eliminates the need to download to Excel and manually calculate these values ​​(the report format can be downloaded to Excel). The dynamic report header clearly indicates what we are analyzing, in what periods, and what we are comparing it to.

  Help Page - A place for easy contact with product and data owners, containing links for quick redirection to other pages present in the report maintenance.




