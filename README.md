# eBay WebScraping and Data Streaming
This is a personal project.

### Goal
The goal of this project is to scrape the product information of "playstation 4 slim" in eBay and saved the data into MySql database.

### Coding Process
- The first step scraped the search result page of "playstation 4 slim" and saved all the product page links into two groups - sponsored and non-sponsored.

- The second step saved all the html files of product page.

- The third step opened the saved product page and scraped the product information such as name, price and number of sold, etc.

- The fourth step cleaned the product information data and saved them into a MySql database.

### Analysis and Result
I used SQL query to extract the statistical summary of "sponsored" and "non-sponsored" items, and concluded that seller score varies significantly between sponsored and non-sponsored items. Non-sponosored group has much higher seller score.
