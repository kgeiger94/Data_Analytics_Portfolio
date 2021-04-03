# Zillow Web Scraping Project

This folder contains a web scraping project that utilizes Beautiful Soup in Python. The purpose of this project was to collect housing data for every state in the United States. There were between 400-600 house listings scraped for each state. After all lsitings were scraped and appended together in a master dataset the final count was over 26,000 listings.

### For data collection, I scraped and collected:
- House Prices
- House Address/State
- House Details (Beds, Baths, SQFT)
- Listing URL/Zillow Link

### The final project goals were:
- Collect around 600 house listings per U.S. state using BeautifulSoup for web scraping
- Perform Exploratory Data Analysis with the housing data
- Create a dynamic dashboard that can be used to search house listings and analyze housing data by state

### There are four parts to this project:
- Part One: BeautifulSoup webs craping of Zillow house listings for each U.S. State
- Part Two: Append all scraped and collected datasets from each state into one master dataset
- Part Three: Exploratory Data Analysis of Zillow house listings from all 50 states
- Part Four: Build a dynamic BI dashboard to search house listings and analyze housing data in all 50 states

### ** Note:

Depending on the time of dashboard use, some listings may not appear or appear inaccurate. These listings were scraped at the same time and listings/prices may have changed or been removed. If this was going to be a live production project and be used on a consistant bases, I would create a pipeline that automated the scraping process on a daily bases and etl the data into a production style database. Then create a live connection from Power BI to the datasource of housing data to keep a live updated dashboard with refreshed Zillow listings.

The overall averages and prices in the final Python notebooks and dashboard do not 100% reflect the actual statistics of housing data in the United States. Due to time constraint, between 400-600 house listings per state were in the final dataset after data cleaning/processing and becuase of the limited data compared to the overall number of listings, appeared to skew the results a little. However, in the final results and averages state by state, the results align with other reputable sources of house statistics. Here are the most and least expensive states according to BusinessInsider.com compared to this projects final results:

##### Business Insider top 10 most expensive states
1. Hawaii
2. Washington DC
3. California
4. Massachusetts
5. Colorado
6. Washington
7. New York
8. Oregon
9. Utah
10. New Jersey

##### Scraped data top 10 most expensive states
1. California
2. Hawaii
3. Washington DC
4. Colorado
5. New York
6. Idaho
7. Utah
8. New Hampshire
9. Rhode Island
10. Massachusetts

### 7/10

##### Business Insider top 10 least expensive states
1. West Virgina
2. Arkansas
3. Ohio
4. Iowa
5. Mississippi
6. Michigan
7. Oklahoma
8. Missouri
9. Indiana
10. Kentucky

##### Scraped data top 10 least expensive states
1. Oklahoma
2. West Virginia
3. Kentucky
4. Iowa
5. Indiana
6. Kansas
7. Mississippi
8. Missouri
9. Ohio
10. Arkansas

### 9/10
