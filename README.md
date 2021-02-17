# Amazing_Brands_Tasks

This project was created at the request of Janik. Below is a decription of each item:

* Amazing_Brands_Task_1:
  Is a simple  scraper that uses python libraries requests and BeautifulSoup. For a given ASIN, it fetches a product's name. It requires two inputs, information from user about their browser and OS, and product ASIN. 
* Amazing_Brands_Task_2:
  Is a scrapy spider that does the same exact thing mentioned in Task_1. However, this code uses scrapy for fetching the source code of the page. It requires two inputs, information from user about their browser and OS, and product ASIN.
* Amazing_Brands_Task_3:
  Is an extention of Task_1. It writes the ASIN, product title, and the time at which the title has been scrapped to an SQLite database right after a title has been scraped. It requires two inputs, information from user about their browser and OS, and product ASIN.
* page:
  Is the page scrapped by scrappy from Task_2.
* product_name:
  Is the database created in Task_3 using SQLite. It contains a table with the cloumbs ASIN, Title, and the Time.
