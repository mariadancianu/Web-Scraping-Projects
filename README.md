# Web-Scraping-Projects
A set of projects to learn and experiment Web Scraping with Python. 

Project  | Description | Dataset size 
------------- | ------------- | -------------
[greatplacetowork-web-scraper](https://github.com/mariadancianu/Greatplacetowork-Web-Scraper) | Scrape companies data | Small 
[rottentomatoes-web-scraper](https://github.com/mariadancianu/Rottentomatoes-Web-Scraper) | Scrape movies data | Small 
[euronics-web-scraper](https://github.com/mariadancianu/Euronics-Web-Scraper) | Scrape smart TV products data from e-commerce platform| Small 

## Technologies 

Python version: 3.11. 

Python libraries:
- BeautifulSoup
- selenium 
- urllib
- pandas

## Status
Project is: *in progress*. 

## Warnings
The websites structure changes in time and a Web Scraper that was previously working perfectly can break due to these updates. The code must be maintained and updated by running periodical tests. Small adjustments are usually required since the websites changes are small and incremental. I will try to update the code periodically but keep in mind that any errors are part of the Web Scraping process.
  

Make sure to check the *robots.txt* file before scraping a website. This standardized file tells you which parts of the website can be scraped and by whom. You can check it out by adding *robots.txt* to the root of the website domain, i.e. https://www.amazon.it/robots.txt. 

  
The *robots.txt* file can contain a crawling delay (a waiting time between crawling actions). Make sure to use a crawling delay (around 5-10 seconds) even if not present in the *robots.txt* file to avoid causing performance issues to the scraped website and getting blocked.  


## Contact 
Created by mary_0094@hotmail.it, feel free to get in touch! :woman_technologist:
