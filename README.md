# Twitter-Scraping-Project1
# Allows to scrape the twitter data and store that in the database and allow the user to download the data with multiple data formats.

# Project Workflow and Execution
This project is a basic web application that performs Twitter scraping, data storage and export functionalities. It is written in Python, using the following libraries: snscrape, pandas, pymongo, streamlit and base64. Below is a workflow and execution plan for the project:

# Workflow
User visits the webpage created by the application
User enters a keyword or hashtag to scrape Twitter data for
User enters a start and end date range for the tweets to be scraped
User enters a tweet count limit
User clicks the "Scrape Tweets" button to initiate the scraping process
The application scrapes Twitter data using the entered parameters
The application displays the scraped data in a table format on the webpage
The user has the option to download the scraped data in CSV or JSON format by clicking on the respective download buttons
The user has the option to store the scraped data in a MongoDB database by clicking on the "Store Tweets" button
If the user chooses to store the data, the application converts the data to a dictionary format and inserts it into a "tweets" collection in the "twitter" database in MongoDB
The application displays a success message if the data is stored successfully

# Execution
Install the necessary libraries: snscrape, pandas, pymongo, streamlit and base64.
Create a MongoDB database with a "tweets" collection.
Copy and paste the code into a Python file named "twitter_scraping.py".
Run the file in a command prompt or terminal using the command "streamlit run twitter_scraping.py".
Access the webpage by clicking on the URL provided in the command prompt or terminal.
Enter a keyword or hashtag, start and end date range, and tweet count limit.
Click on the "Scrape Tweets" button to initiate the scraping process.
View the scraped data in a table format on the webpage.
Click on the "Download CSV" or "Download JSON" button to export the scraped data in the respective format.
Click on the "Store Tweets" button to store the scraped data in the MongoDB database.
