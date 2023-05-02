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
  
![image](https://user-images.githubusercontent.com/121142680/235782069-dff1f457-9b9e-45b7-ace7-a435c20d58da.png)

  2. How many Martian days worth of data exist in the dataset?
  
![image](https://user-images.githubusercontent.com/121142680/235782141-6ba0151f-57b1-4c9c-9780-bd8ec30fa41d.png)
  
  3. What are the coldest and warmest month on Mars?
   
![image](https://user-images.githubusercontent.com/121142680/235782238-f60593b3-bf6f-4c3e-84af-d16b12a6c11d.png)
   
  4. Which months have the lowest and highest atmospheric pressure on Mars?
   
![image](https://user-images.githubusercontent.com/121142680/235782316-2bd7e556-ef8d-4dbe-aa64-03b56d8ac7f6.png)
   
  5. About how many terrestrial days exist in a MArtian year?
  
![image](https://user-images.githubusercontent.com/121142680/235782389-991f8575-ff40-4315-8366-54b0ef137a02.png)
![image](https://user-images.githubusercontent.com/121142680/235782449-81d09688-3b7f-4184-b423-4236e257a948.png)

  
 * Export DataFrame as CSV file ([mars_temp_data.csv](https://github.com/StanJohn04/Mars-Webscraping-Challenge/blob/main/MarsData/Resources/mars_temp_data.csv)).
 
