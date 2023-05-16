# Presidential Data
We have a datasheet here with data on presidents and I'm going to clean up the worksheet to be able to properly import it to SQL and Tableau


***

- Began with removing duplicate data. Went to the Data ribbon and pressed remove duplicates
- Standardizing the president column by copying it over and running a =PROPER function on it because I see that there are lowercases and uppercases everywhere
- Cleaned party column by correcting misspellings and allocating them into the intended party categories
- Created new column and trimmed on vice column to remove extra spaces everywhere on the column
- Edited the salary column by changing the whole column from being a currency to a number and then removing decimals for better readability and flexibility down the line
- Went to the date updated and date created and set everything to short date so theres consistency 

<details>
  <summary>
    Open Image
  </summary>

![proper](https://github.com/vtn160230/COVID-19/assets/122754787/aade8f7e-70d8-4ce3-b4f6-aafc3afc5f2b)

</details>

***

