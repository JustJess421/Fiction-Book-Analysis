# Fiction-Book-Analysis
Analyzing top rated books for new bookshop.

Bookshop Analysis
 
Scenario:
A new bookshop is opening in town and the owner would like an analysis of the most popular genres for fiction and non-fiction books. They would also like top rated books in those genres to display in the store to jump start sales.  
 
Data:
The dataset that was used was the “Amazon 50 Top Bestselling Books from 2009-2019”. This data set shows the Name, Author, User Rating, Reviews, Price, Year, and Genre (fiction or non-fiction). 
 
Analysis:
Below is the SQL used in BigQuery to clean and filter the data for fiction books. I wanted to add in specific genres other than fiction and nonfiction, so I filtered and saved a table to get rid of duplicates, only pull the column for Name and only the fiction genre. I then added the different genre types by conducting Google searches on the books and adding to the table. Once the table was complete, I uploaded into BigQuery and joined my new table with the original table to add the column “Genre_Type”. I then used the COUNT and SUM functions to complete the analysis. 
 
Link to Final Table:
Final_Books_Fiction
 
