# dallas-house-prices
Scrapes data from a certain popular real estate website and some exploratory analysis.

(scrape at your own risk)

## Tools
BeautifulSoup, Pandas, Matplotlib

## dallas-homes
Script that loops through each page and saves the html content as a dictionary. To avoid crashing their server or causing any issues I kept this under 20 pages. 

Each listing was scraped for the following data:
* Address
* City, state, zipcode
* Beds
* Baths
* Price 

## dallas-housing-market
Exploratory data analysis that looks at: 
* The distribution of housing prices in the Dallas area 

## Future projects
* Past data or data in a few years to see how housing prices in Dallas have changed over time 
* Scrape nearby areas to compare inner city to suburban housing prices
* Scrape data from another city/state and compare 