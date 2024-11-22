**Data Cleaning Guideline**

By general rule we will follow the [Golden Record Standard.](https://docs.google.com/spreadsheets/d/13Ad0WeOOEWXXT29LlIaDmT3KqQHzb9Af8BKq7Kb34A0/edit?gid=1657912520#gid=1657912520)

Some specific comments made by Equifax: 

1. SSN: 9 digits including the leading 0 without '-' 
2. Dates: in yyyymmdd format and in Date format. 
3. States: Use 2-letter state codes (e.g., NY, CA, FL).
4. Ages from dob and create age bucket 
5. If there is address 1 and address 2, create a new column calles address_full or all in address 1 for GR standard 
6. Names according to the Golden Record Variable Name (snake_case format)
7. Export with pipe or tab 