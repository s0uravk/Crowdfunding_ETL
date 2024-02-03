# Crowdfunding_ETL

![ETL](https://miro.medium.com/v2/resize:fit:700/1*e8tYHCzBQiyEVPNKctYPRg.png)

This project revolves around the Extract, Transform and Load process of Data. As the name suggests, Data is imported to Jupyter Notebook and transformed accordingly then exported as CSV files. Then, the schema is created to load those CSV files to a database for storage and further use. 

At first, Data is imported from an Excel file in the Resources folder, and the category & subcategory columns are split into two columns based on category and subcategory separated by '/'. Then two new data frames are created for each category and subcategory with the id for each category and subcategory in their respective data frame and exported as CSV files. Next, some columns are renamed, the datatype is changed for some columns, and launched_date and end_date columns are converted into datetime datatype. For the final step, subcategory and category data frames are merged into the resulting data frame on the subcategory and category columns respectively. Unnecessary columns are dropped and the data frame is exported as a CSV file.

Then for the second part of the Project, An Excel file is imported and all the data is merged into one column. It can be separated using Python dictionaries and Regular expressions. While using Python dictionaries, each row is converted into a dictionary and appended to a list, which is then converted into a pandas data frame.
