# datacollection-challenge
## What You're Creating

This assignment consists of two technical products:

* Deliverable 1: Scrape titles and preview text from Mars news articles.

* Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.
Instructions
## Part 1: Scrape Titles and Preview Text from Mars News

* Use automated browsing to visit the Mars news site. Inspect the page to identify which elements to scrape.
Create a Beautiful Soup object and use it to extract text elements from the website.

* Extract the titles and preview text of the news articles that you scraped. Store the scraping results in a Python dictionary and, give each dictionary two keys: title and preview 


## Part 2: Scrape and Analyze Mars Weather Data

* Use automated browsing to visit the Mars Temperature Data. Inspect the page to identify which elements to scrape.
Create a Beautiful Soup object and use it to scrape the data in the HTML table. 
Assemble the scraped data into a Pandas DataFrame. 
    - Here’s an explanation of the column headings:
        - id: the identification number of a single transmission from the Curiosity rover
        - terrestrial_date: the date on Earth
        - sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
        - ls: the solar longitude
        - month: the Martian month
        - min_temp: the minimum temperature, in Celsius, of a - single Martian day (sol)
        - pressure: The atmospheric pressure at Curiosity's location
- Examine and change the data types that are currently associated with each column if needed.
- Analyze your dataset by using Pandas functions to answer the following questions:
- How many months exist on Mars?
- How many Martian (and not Earth) days worth of data exist in the scraped dataset?
- What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
- Which months have the lowest and the highest atmospheric pressure on Mars? 
- About how many terrestrial (Earth) days exist in a Martian year?
- Export the DataFrame to a CSV file.

