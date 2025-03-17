**NASA API Web Scraper**

**Overview**

This project fetches and analyzes space-related data using NASA's public API. The data includes information on asteroids, astronomical pictures of the day, and other space-related insights. The goal is to demonstrate API data retrieval, processing, and basic analysis using Python.


**Features**

1. Fetches Astronomy Picture of the Day (APOD) and Near-Earth Object (NEO) data.

2. Uses Requests to interact with NASA's API.

3. Processes JSON responses and extracts relevant data.

4. Analyzes asteroid data, including element counts and close approaches.
   

**Technologies Used**

-Python

-Pandas (for data manipulation)

-Requests (for API calls)

-Jupyter Notebook


**How to Run the Project**

**Step_1**: Clone this repository:

git clone https://github.com/yourusername/nasa-api-webscraper.git
cd nasa-api-webscraper

**Step_2**: Install required dependencies:

pip install pandas requests

**Step_3**: Run the Jupyter Notebook to fetch and analyze NASA API data.


**Sample API Endpoints Used**

1. Astronomy Picture of the Day (APOD):

https://api.nasa.gov/planetary/apod?api_key=YOUR_API_KEY

2. Near-Earth Object (NEO) Feed:

https://api.nasa.gov/neo/rest/v1/feed?start_date=YYYY-MM-DD&end_date=YYYY-MM-DD&api_key=YOUR_API_KEY


**Results**

-Extracted and displayed NASA's Astronomy Picture of the Day.

-Processed asteroid approach data, including the total count and details of close approaches.


**Future Improvements**

-Add visualizations using Matplotlib/Seaborn.

-Store results in a structured database.


**Author**

Grace Muthina
