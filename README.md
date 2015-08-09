# QuoraCrawler

---

This project makes use of the Selenium and chromedriver to crawl data from quora.com and find the questions with the most upvotes. 

It starts at a specified root topic and traverses the child topics to build a hierarchy tree. 

It will first crawl and scrape all the questions within all the topics. 

Meanwhile, it maintains a list of users who have either asked a question, answered, or upvoted. After crawling the questions, it will crawl and scrape all the users.


## Requirements
- selenium https://github.com/seleniumhq/selenium

- chromedriver https://sites.google.com/a/chromium.org/chromedriver/

- beautifulsoup http://www.crummy.com/software/BeautifulSoup/

## Usage:
- python quoraCrawl.py

## Notes:
As the pages change frequently, this project may not necessarily be able to use directly, so you need to modify certain pages according to the actual situation.
