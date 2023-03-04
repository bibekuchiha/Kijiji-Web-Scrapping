# Title: Scraping Kijiji Rental Data and Conducting Exploratory Data Analysis

### Introduction:
Kijiji is a popular online marketplace where people can buy and sell items or services in Canada. It is owned by eBay and is a well-known platform for buying and selling real estate. This project is about scraping Kijiji rental data and conducting exploratory data analysis.

### Project Objective:
The objective of this project is to scrape Kijiji rental data for the city of Toronto and conduct exploratory data analysis on the collected data. We aim to gain insights into the rental market in Toronto by analyzing the prices, locations, and other features of rental properties.

### Technologies and Libraries Used:

- Python programming language
- Requests library for HTTP requests
- BeautifulSoup library for web scraping
- TQDM library for displaying progress bars
- Pandas library for data manipulation and analysis
- Matplotlib and Seaborn libraries for data visualization
### Methodology:
The project is divided into two main parts. The first part is web scraping, where we collect the rental data from Kijiji's website. The second part is exploratory data analysis (EDA), where we analyze the collected data and derive insights.

### Web Scraping:
To scrape Kijiji rental data, we used the Requests and BeautifulSoup libraries in Python. We created a function that takes in the city name, property type, and page number as inputs and returns the parsed HTML content of the page. We then iterated over multiple pages of rental listings, scraping the data for each rental property and storing it in a list.

### Exploratory Data Analysis:
After scraping the data, we loaded it into a Pandas DataFrame and performed some data cleaning. We removed the dollar sign and comma from the price column, replaced "Please Contact" values with NaN, and removed leading/trailing spaces and line breaks from the location column. We also removed unnecessary text from the location column and converted the price column to a numeric data type.

We then conducted some exploratory data analysis on the cleaned data. We visualized the distribution of prices using a histogram and plotted the frequency of rental properties by location using a bar chart. We also plotted the average price by location using a bar chart.

### Insights:
From the EDA, we gained several insights into the rental market in Toronto. We found that the distribution of prices is positively skewed, indicating that most of the rental properties have lower prices. We also found that the maximum number of rentals and housing are available in Toronto and Brampton. Finally, we found that the average rental price varies widely across different locations in Toronto, ranging from around $1500 to $3000.

### Conclusion:
This project demonstrates the use of web scraping and exploratory data analysis techniques to gain insights into the rental market in Toronto. The insights gained from this analysis can be useful for renters and landlords alike to make informed decisions regarding rental properties. The code used in this project can be adapted to other cities and property types to conduct similar analyses.
