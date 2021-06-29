# stock-market-data
The data is scraped from multiple websites like money control and yahoo finance.

* **Money Control Scraping Stocks Links.ipynb** - scraps all links for all the stocks ever listed on NSE/BSE.

* **Money Control Categories Scraping via Links.ipynb** - uses the links scraped from above and scraps the stocks data like name, sector, and strong sector and last updated (There are 8000+ links so this takes a large amount of time)

* **Money Control Scrap Daily Change Category.ipynb** - scraps the stocks daily price and their change based on the category . You can find the data (from 25 May 2021) on Kaggle [NSE BSE Stocks daily change](https://www.kaggle.com/apoorvgupta25/nse-bse-stocks-daily-change)

* **Yahoo Finance Scrap.ipynb** - scraps the NSE stocks category from yahoo finance (get the [list](https://www.nseindia.com/regulations/listing-compliance/nse-market-capitalisation-all-companies) of NSE stocks ), BSE stocks [list](https://www.bseindia.com/corporates/List_Scrips.html) already has a category
