# About
This is a collection of web scraping notes & examples in Jupyter Notebooks. Typical approaches for obtaining online data are:
1. Public API
2. Ready data file (XML, JSON, CSV, etc.)
3. Web Scraping

If method 1 and 2 are not available as the owner doesn't expose their data, the only possibility is through the web scraping techniques. Despite of the typical request + analyzing html method, there are cases where we might need to automate user behaviors due to cookies setting, ajax call or defered rendering which require simulated browser to handle.

# Comparison between different libraries/Framework
This notebook will show the differences in syntax with different tools:
1. BeautifulSoup
2. Scrapy (Xpath/ CSS pseudo-element)
3. Selenium with ChromeDriver

Refer to file "**_main_comparison.ipynb_**"

# Case studies
## Example 1: Scrapy to extract quotes
Extract quote statements in [Quotes to Scrape](http://quotes.toscrape.com) and save in local json file with fields:
* Statement 
* Author
* Author Page
* Tags

Refer to file "**example_quotes_to_scrape.ipynb_**"

## Example 2: Selenium to extract reviews
Extract reviews in [Trip Advisor](https://www.tripadvisor.com.sg/) and save in local json file with fields:
* Username 
* Rating
* Title
* Description
* Created Date

Refer to file "**example_tripadvisor.ipynb_**"
