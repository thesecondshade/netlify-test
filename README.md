# Flashpoint Code Assessment: Classic Car Forum Scraper

 Classic Car Forum Scraper is a script written that allows you to scrape each post from the Classic Car Forum Scraper.

This script is written in python3 and utilizes the python modules, "BeautifulSoup" and "requests". The output results of this script are written to a comma-separated-values (CSV) file named “thread.csv” which lists the posts by row with these required fields:
```
['post id', 'name',' date of the post', 'post body'].
```


## Prerequisites

Before you begin, ensure you have met the following requirements listed in the requirements.txt file:
```
beautifulsoup4==4.9.3
bs4==0.0.1
certifi==2020.12.5
chardet==4.0.0
idna==2.10
requests==2.25.1
soupsieve==2.2
urllib3==1.26.3
pytest==6.2.2
```


## Using Classic Car Forum Scraper

To use Classic Car Forum Scraper, follow these steps:

```
pip install requirements.txt
python3 flashpoint_webscraper.py
```

## Testing Classic Car Forum Scraper
The python testing module "pytest" was used to write the testing on this project. The scraping sample that was taken from the Classic Car Forum,  'soup_test.txt', is stored in 'test_resources'.

To test Classic Car Forum Scraper, follow these steps:

```
pytest test.py
```
