# DataCleaning-using-Excel
### About
In this project, I am using Microsoft Excel for performing data cleaning operations in a macro and save the file as Macro enabled Excel file. Data cleaning is the process of identifying and correcting errors, inconsistencies, and inaccuracies in a dataset to improve data quality and reliability. 
### Introduction
Data cleaning is an essential part of the data analysis process. It ensures that the dataset is accurate, complete, and properly formatted, enabling meaningful analysis and decision-making, involves a series of steps such as data validation, data transformation, data normalization, and data enrichment. Data cleaning is a critical step in data preprocessing and is often performed before data analysis or Machine Learning algorithms are applied to the data. Excel, with its wide range of functionalities and intuitive interface, offers several powerful features for data cleaning tasks.
### Key Features
* Wide Accessibility: Microsoft Excel is a widely accessible and commonly used spreadsheet application, making it accessible to a large user base. The familiar interface and diverse functionalities of Excel enable users to perform various data cleaning tasks effectively.
* Data Cleaning Techniques: Handling missing values, getting rid of duplicates, fixing inconsistent formatting, validating data entries, utilising formulas and functions, utilising conditional formatting, sorting and filtering data are all examples of data cleaning techniques.
* User-Friendly Interface: Excel's user-friendly interface makes it easy to use even for individuals without extensive programming or technical skills. Excel's graphical design allows users to visually identify and manipulate data.
* Flexibility and Customization: Excel offers extensive flexibility, allowing users to customise their data cleaning process to individual needs. The ability to apply formulas, functions, and conditional formatting allows customers to tailor the data cleaning process to their own requirements.
### Prerequisites
Before begin, ensure that we have the following prerequisite:
* Excel
### Step-by-Step Guide to Clean Data using Excel
##### Step 1: Open the Dataset
Launch Excel and open the dataset which have to clean. We can open various file formats, such as Excel workbooks (.xlsx), CSV files, or text files, using the "Open" option in the "File" menu.
##### Step 2: Before data cleaning, dataset is shown below
![image](https://github.com/shaheeneqbal/DataCleaning-using-Excel/assets/67499556/73a7b6e2-1c2b-41db-98d2-1887e2855e51)
##### Step 3: Identify Data Quality Issues
Examine the dataset to identify any possible problems with data quality. This may include missing values, inconsistent formatting, invalid entries, etc.
##### Step 4: Operations on Name and Age columns
In name column where names are missing, filling the value in place by extracting the name from the Email-id column. And, filling the missing Age value with the mean of the Age column.
##### Step 5: Operations on Phone column
Cleaning and formatting phone number column as some entries are in string and some are in number format. And, all entries showing like (91-xxxxxxxxxx).
##### Step 6: Deleting Rows
In columns Name and Email-id where both are missing, deleting the entire rows.
##### Step 7: Operations on Salary column
In the salary column, highlighting the top 10 employees with highest salary in the dataset.
##### Step 8: Operations on Email-id and Address columns
Where name is there but no Email-id then filling the blanks with "support@dataisgood.com". And, where address is not there filling it with "Address not Available".
##### Step 9: Operations on Department column
In the Department column, making the data PROPER with the useful functions and rename the wrong spelled words.
##### Step 10: After data cleaning, dataset is shown below


### License
This project is licensed under the MIT License. Feel free to modify and use it as per your requirements.
### Conclusion
Data Cleaning Using Excel equips users with the knowledge and resources necessary to perform data cleaning tasks effectively. By leveraging the powerful features of Microsoft Excel, users can enhance data quality, resolve inconsistencies, and prepare datasets for accurate analysis. This repository provides valuable insights and techniques to streamline the data cleaning process using Excel. 
