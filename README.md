Web Scraping Assignment

The python script scrapes data from https://en.wikipedia.org/wiki/2019_in_spaceflight#Orbital_launches to analyze data in the 'Orbital Launches' table and get number of distinct launches each day, provided atleast one of the payloads of each launch have a specific desired outcome.

Libraries used:

Scrapy : To scrape HTML content from a web page

Beautiful Soup : To parse HTML content

Pandas : A python library for data manipulation and analysis (groupby, daterange, count, merge)


Output:

CSV file containing dates in the year 2019 in ISO format and corresponding number of distinct orbital launches satisfying the given criteria.
