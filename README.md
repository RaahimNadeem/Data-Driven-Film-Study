# Data Driven Film Study
![image](https://github.com/RaahimNadeem/Data-Driven-Film-Study/assets/114340940/2a191539-fc22-4869-adb9-b6a4eac0078e)

## Blog Overview
This project aims to provide data-driven insights and recommendations. The primary objectives are to analyse the attributes of top-grossing movies from the past decade, including genre, creative type, production method, release month, and production budget, to determine which factors contribute to high box office performance. Through rigorous analysis, we aim to identify which elements significantly impact a movie's financial success. By extrapolating from this analysis, we intend to offer concrete recommendations specifically tailored to various types of films. Ultimately, our objective is to furnish valuable insights rooted in data to help the target audience make well-informed decisions about entering and/or thriving in the filmmaking business.

## Technical Tools and Methods used
For the data collection project aimed at gathering movie industry data from The Numbers - Where Data and the Movie Business Meet (the-numbers.com), we will primarily use web scraping tools and techniques. Specifically, we will employ Python along with the following libraries:
- requests: To send HTTP requests and retrieve web page content.
- BeautifulSoup: To parse and extract relevant data from the HTML structure of the web pages.
- pandas: To store, manipulate, and analyse the collected data efficiently.

The data collection process involves sending HTTP GET requests to the-numbers.com to retrieve the web pages that can be scraped for the top 100 grossing movies for a range of years and then using the BeautifulSoup library in python to parse the content and extract specific data, which can then be exported to DataFrames (using pd.read_html) for easy analysis.

For each year, we scrape this information for the top 100 movies according to their box office performance.

## Medium Blog Link
https://medium.com/@raahim.nade/data-driven-film-industry-study-b09b56bc4b0d
