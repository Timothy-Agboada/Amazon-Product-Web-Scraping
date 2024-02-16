# Amazon-Product-Web-Scraping
Repo for a web scraper that takes the product name and price daily into a csv file while taking note of the day the data was taken.

# Overview
* The model provides a csv file that contains the data tracking of a product and its price daily.
* The web scraper also contains a script that alerts a particular email about a drop in price to a specified threshold.
* The intents and purpose of this scraping is to analyze and visualize the price changes, and by extension the discount analyses offered by Amazon on certain products.
* Libraries such as BeautifulSoup, pandas and smtplib were used in this project.

# Notes
* Although a specific url is used for this model, it can be easily altered to cater to other links based on the id and class values.
* Data was extracted from Amazon.com
