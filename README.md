# KPMG-AU-Data-Analytics-Task
Preliminary data exploration and improving the quality of a large dataset in preparation for analysis.

Client provided 3 datasets:
1.Customer Demographic
2.Customer Addresses
3.Transactions data 

The task is to identify data quality issues and highlight how to mitigate these issues

The first analysis is the Transactions dataset :
- There are missing values in 7 columns. They can be dropped or treated according to the nature of analysis
- There are no duplicate values, so the data is unique.
- The values in the product_first_sold_date columns are not accurate as it shows all products were sold on the same day

NewCustomersList
- There are missing values in 4 columns. They can be dropped or treated according to the nature of analysis
- There are no duplicate values.
- There are 17 columns with unknown/unspecified gender.

CustomerDemographic
- There are 17 columns with unknown/unspecified gender.
- There are no duplicate values.
- Certain categories are not correctly titled. The names in these categories are re-named.
- Values are inconsistent in some columns, hence dropping the columns.
- Histogram shows that there are Outliers. DOB of 1840s, 1920s, 1940s.

CustomerAddress
- There are no null values.
- There are no duplicate values.
- All the columns appear to have consistent and correct information.
