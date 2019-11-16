# Scraping eBay

This project uses python scripts to scrape Ebay's products data using the Scrapy Web Crawling Framework

An example of the scraped data can be found in the ***data/*** folder.

The image below shows the scraped data for the *"iphone X 256gb"* search string in ebay.com

![ebay_iphone_x_256gb_products_sample](https://user-images.githubusercontent.com/22003608/45721730-a6e3fc80-bb7f-11e8-8e8f-50103bf7c842.jpg)
)

The default search string is *Apple Airpods* and it can be changed in the command line with the *-a* flag.
For example, to search for an *Playstation 4* you can use:

*scrapy crawl ebay -o products.csv -a search="Playstation 4"*
