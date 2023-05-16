# Presidential Data
We have a datasheet here with data on presidents and I'm going to clean up the worksheet to be able to properly import it to SQL and Tableau


***

- Began with removing duplicate data. Went to the Data ribbon and pressed remove duplicates
- Standardizing the president column by copying it over and running a =PROPER function on it because I see that there are lowercases and uppercases everywhere
- Cleaned party column by correcting misspellings and allocating them into the intended party categories
- Created new column and trimmed on vice column to remove extra spaces everywhere on the column
- Edited the salary column by changing the whole column from being a currency to a number and then removing decimals for better readability and flexibility down the line
- Went to the date updated and date created and set everything to short date so theres consistency 
- Last I removed the prior column as I believed it was not something useful or worthwhile


***

