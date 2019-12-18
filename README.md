# ShoppingCrawl
The sample program to scrap information from the bookstore.

# Description
Shopping Scraper shortcutsthe simple scrapping example from a bookstore. The output will be store in to the csv file in the current directory.

# Setting up:

Environment: 
Python 3+

If you have two version of Python installed. Here is the instruction creating virtual environment for the python 3 and run the
spider. 

To check Python version:
~$ python -v

To install the virtual environment:
~$pyenv myenv
~$source ./myenv/bin/active

To instal the required package:
(myenv)~$pip install scrapy

To run the spider:
scrapy crawl bookscraper-css

The output is in the booksdata.csv file.
