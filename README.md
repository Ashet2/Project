# Commercial Analysis Project
Problem Summary:
In the context of analyzing postpaid customers of an electricity distribution company, there is a need to consolidate data from multiple Excel tables, extract relevant information, and perform various analytical tasks to answer critical business questions. The key problems to address include:

Data Integration: Five separate Excel tables contain data related to postpaid customers and feeder information. The challenge is to merge these tables into a single comprehensive dataset for analysis.
Data Extraction: Specific columns, such as feeder bands and names from 11kV Feeders and 33kV Feeders tables, need to be extracted and concatenated.

Enrichment: The combined feeder list needs to be merged with the postpaid customer list to provide additional customer-related information.
Payment History: The payment history table must be integrated into the postpaid customer listing to analyze customers' payment patterns.
Data Export: The final dataset from the above processes must be exported to an Excel file for further analysis.

Solution Summary:
To address the above problems, the following steps were executed using Python:
Data Integration: Python and its libraries were employed to read and combine data from the five Excel tables into a comprehensive report. Common columns for merging were identified to ensure data alignment.

Data Extraction: Relevant columns (feeder bands and feeder names) from the 11kV and 33kV Feeder tables were extracted, and the tables were concatenated to create a consolidated feeder list.

Data Enrichment: The consolidated feeder list was merged with the postpaid customer list, enriching customer data with feeder-related information.

Payment History Integration: The payment history table was merged with the postpaid customer listing to provide insights into customers' payment patterns.

Data Export: The final enriched dataset was exported to an Excel file, enabling further analysis to answer various business questions.

Outcome:
The resulting "Merged Postpaid Customers" dataset is clean, manipulated, and comprehensive. It allows for analyzing customer demographics, payment behaviour, and regional distribution, enabling insights into customer types, tariff categories, revenue collection, and more. This data-driven approach supports informed decision-making for the electricity distribution company.