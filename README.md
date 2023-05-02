# Mars-Webscraping-Challenge
# Background
The goal of this challenge is use the python libraries Splinter and BeautifulSoup to extract and parse HTML from websites. After collecting the data, it will need to be organized and stored before analyzing and visually communicating insights.

This challenge consists of two deliverables:
  * Deliverable 1: Scrape titles and preview text from Mars news articles
  * Deliverable 2: Scrape and analyze Mars weather data, which exists in a table
  
# Part 1:
Jupyter Notebook: [part_1_mars_news](https://github.com/StanJohn04/Mars-Webscraping-Challenge/blob/main/MarsData/part_1_mars_news.ipynb)

  * Using automated browsing, visit the [Mars news site](https://static.bc-edx.com/data/web/mars_news/index.html).
  * Create beautiful Soup object and extract text elements
  * Extract the titles and preview text of the news articles. Store the scraping results in Python list
  * Export scraped data as [JSON](https://github.com/StanJohn04/Mars-Webscraping-Challenge/blob/main/MarsData/Resources/mars_news.json)

# Part 2:
Jupyter Notebook: [part_2_mars_weather](https://github.com/StanJohn04/Mars-Webscraping-Challenge/blob/main/MarsData/part_2_mars_weather.ipynb)

 * Using automated browsing visit the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html)
 * Create a Beautiful Soup object and scrape the data in the HTML table.
 * Assemble the data into a Pandas DataFrame
   * Make sure Columns have proper headings and datatypes

![image](https://user-images.githubusercontent.com/121142680/235781278-a978efe7-9c71-433e-8230-16a856fc6bae.png)
 
 * Analyze the dataset using Pandas and answer the following questions:
   1. How many months exist on mars?
   2. How many Martian days worth of data exist in the dataset?
   3. What are the coldest and warmest month on Mars
   4. Which months have the lowest and highest atmospheric pressure on Mars?
   5. About how many terrestrial days exist in a MArtian year?
 * Export DataFrame as CSV file.
 
