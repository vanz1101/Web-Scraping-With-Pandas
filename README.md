# Web-Scraping-With-Pandas

For this personal project I used python pandas library to scrape data from wikipedia using read_html() function that brought in the available tables in the website then
sliced the tables and to get the list of largest companies in the US.
I was able to get all the values of the wanted table except the Revenue Growth which returned NaN. 
I saved my table as a dataframe and into the machine using the to_csv() function.
After adding a flavor ('bs4') I was able to pull the missing column.
