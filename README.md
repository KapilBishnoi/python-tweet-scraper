# python-tweet-scraper


## Follow the below steps to setup python-tweet-scraper


### 1. Install [Python 3](https://www.python.org/downloads)

### 2. Install [Selenium for Python](https://pypi.python.org/pypi/selenium)


### 3. Download [Webdriver for Chrome](https://sites.google.com/a/chromium.org/chromedriver/)

### 4. Copy chromedriver executable to the root path of this repository


### 5. Copy complete URL from the Twitter Advanced Search result and paste in twitter-advanced-search-url.txt

This URL will show all the tweets to be downloaded

twitter-advanced-search-url.txt will have only ONE line i.e. URL of Twitter Advanced Search result page


### 6. Execute the below command from command line
 
python python-tweet-scraper.py


### 7. A csv file will get generated with current timestamp in the name, this file will have all the tweets from the result page of Twitter Advanced Search.