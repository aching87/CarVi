#README
This README gives an overview of the files/code included in this folder

###CarVi.ipynb
This file includes code to do some basic data analysis, look at slices of the data in each table, and merge tables. The goal is to build a basic understanding of CarVi's data for someone new to the data. It might be useful to look at the CarVi Data Key while working through this code. It can also be used to explore specific sets of data (e.g. a specific camera_id, a certain time/day, etc).

###CarVi.BuildDataFrame.ipynb
This file includes code to process the rows of data into a dataframe that is more useful for some types of modeling (contains some summary info instead of the row-by-row data).

###Data_Integrity_Check.ipynb
This file includes code to check that the data is clean. Based on the data science team's understanding of the data (as specified in the Data Key), it processes data integrity checks and returns data that does not pass the check. This will help the data team talk to the engineers about any inconsistencies and/or modify our understanding of the data. 

###Distribution_Checks.ipynb
Similar to Data_Integrity_Check.ipynb, this code checks that the data is clean, but requires a more manual review of the data to check for integrity and outliers. It outputs the tables' summary statistics and distributions (counts, histograms, boxplots). 
