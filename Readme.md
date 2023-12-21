Module 11 - web-scraping-challenge

This assignment consisten of two technical products
Deliverable 1: Scrape titles and preview text from Mars news articles.¶
Deliverable 2: Scrape and analyze Mars weather data, which exists in a table

Part 1: Scrape Titles and Preview Text from Mars News
1. Use automated browsing to visit the Mars news site - https://static.bc-edx.com/data/web/mars_news/index.html. Inspect the page to identify which elements to scrape.
2. Create a Beautiful Soup object and use it to extract text elements from the website.
3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures.
 
Part 2: Scrape and Analyze Mars Weather Data
1. Use automated browsing to visit the - https://static.bc-edx.com/data/web/mars_facts/temperature.html. Inspect the page to identify which elements to scrape.

2. Create a Beautiful Soup object and use it to scrape the data in the HTML table.

3. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website:
id - the identification number of a single transmission from the Curiosity rover
terrestrial_date - the date on Earth
sol - the number of elapsed sols (Martian days) since Curiosity landed on Mars
ls - the solar longitude
month - the Martian month
min_temp - the minimum temperature, in Celsius, of a single Martian day (sol)
pressure - the atmospheric pressure at Curiosity's location

4. Examine the data types that are currently associated with each column. Covert the data to the appropriate dateime, int, or float data types.

5. Analyze your dataset by using Pandas functions to answer the following questions:¶

How many months exist on Mars? - 12 months

How many Martian (and not Earth) days worth of data exist in the scraped dataset? - 1,867 days

What are the coldest and the warmest months on Mars (at the location of Curiosity)?
The coldest month is 3.
The warmest month is 8.

Find the average minimum daily temperature for all of the months.

![image](https://github.com/eferna1/web-scraping-challenge/assets/145945547/508dc8c7-df63-4b4e-804b-0d115b0b7c24)

Plot the results as a bar chart.

![image](https://github.com/eferna1/web-scraping-challenge/assets/145945547/d495911e-dc34-4854-a19a-bfbe7506399e)

Which months have the lowest and the highest atmospheric pressure on Mars?
Lowest month with atmospheric pressure is month 6.
Highest month with atmospheric pressure is month 9.

Find the average daily atmospheric pressure of all the months.

![image](https://github.com/eferna1/web-scraping-challenge/assets/145945547/79868e55-d398-4213-b2a0-f196d730a4f5)

Plot the results as a bar chart.

![image](https://github.com/eferna1/web-scraping-challenge/assets/145945547/4d172447-cbdb-43c5-b0d0-5cc96a0ca8e8)

About how many terrestrial (Earth) days exist in a Martian year? 675 days.
Consider how many days elapse on Earth in the time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature.

![image](https://github.com/eferna1/web-scraping-challenge/assets/145945547/d19fbc66-b8e2-4538-a5ae-b3b76d6c03a7)
