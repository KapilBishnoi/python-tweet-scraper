# python-tweet-scraper


Follow below steps to setup python-tweet-scraper


Install Python 3 (https://www.python.org/downloads)

Install Selenium for Python https://pypi.python.org/pypi/selenium


Download Webdriver for Chrome from https://sites.google.com/a/chromium.org/chromedriver/

Copy chromedriver executable to the root path of this repository


Copy complete URL from the Twitter Advanced Search result and paste in twitter-advanced-search-url.txt

This URL will show all the tweets to be downloaded

twitter-advanced-search-url.txt will have only ONE line i.e. URL of Twitter Advanced Search result page


Execute below command from command line
 
python python-tweet-scraper.py


A .csv file will get generated, this file will have all the tweets from the result page of Twitter Advanced Search.