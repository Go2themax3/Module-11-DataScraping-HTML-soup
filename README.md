Web-Scraping and Data Analysis: Mars Exploration
Overview
The main objective of this project is to showcase web-scraping skills combined with data analysis. We focus on extracting information from a website dedicated to Mars news and another displaying Mars weather data. The tools of choice for this project are Beautiful Soup for HTML parsing, Splinter for automated browsing, and Pandas for data analysis.

What's Inside:
Deliverable 1: Mars News Scraping
Objective: Extract the latest Mars news articles' titles and preview texts.

Steps:

Use Splinter to automate the web browsing process to the Mars news site.
With Beautiful Soup, identify and extract the titles and previews.
Store each title and preview text pair as dictionaries in a list.
Optionally, save this data as a JSON file for sharing.
Deliverable 2: Mars Weather Data Analysis
Objective: Scrape and analyze Mars weather data.

Steps:

Use Splinter to navigate to the Mars temperature data site.
Use Beautiful Soup to scrape the HTML table containing weather data.
Convert this data into a Pandas DataFrame and ensure columns match the website's table headings.
Adjust data types as necessary, such as converting strings to datetime or numeric formats.
Analyze the data to answer specific questions related to Mars weather patterns.
Data Analysis Questions:
Mars Months: Determine the number of months on Mars.
Martian Days: Calculate the total number of Martian days (sols) present in the dataset.
Temperature Trends: Identify the coldest and warmest months on Mars based on the average daily minimum temperature. This will be visualized using a bar chart.
Atmospheric Pressure Trends: Determine which months have the highest and lowest average atmospheric pressures. Results will be depicted in a bar chart.
Mars vs Earth Year: Estimate the number of Earth days in a Martian year by examining temperature patterns.

Files and Instructions:

Starter Code: Two Jupyter Notebooks named part_1_mars_news.ipynb and part_2_mars_weather.ipynb.
Instructions:
For Mars news scraping, open part_1_mars_news.ipynb and follow the steps outlined.
For Mars weather data analysis, open part_2_mars_weather.ipynb and execute the described procedures.
Final Notes:
This project integrates various data analysis skills. First, by collecting and organizing data through web scraping and then analyzing and visualizing the data to uncover patterns. The focus on Mars serves as an exciting backdrop to this exploration.
