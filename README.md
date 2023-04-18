# Twitter-Scraping-Project1
Allows to scrape the twitter data and store that in the database and allow the user to download the data with multiple data formats.

# Project Workflow and Execution
This project is a basic web application that performs Twitter scraping, data storage and export functionalities. It is written in Python, using the following libraries: snscrape, pandas, pymongo, streamlit and base64.

Below is a workflow and execution plan for the project:

# Workflow
1. User visits the webpage created by the application
2. User enters a keyword or hashtag to scrape Twitter data for
3. User enters a start and end date range for the tweets to be scraped
4. User enters a tweet count limit
5. User clicks the "Scrape Tweets" button to initiate the scraping process
6. The application scrapes Twitter data using the entered parameters
7. The application displays the scraped data in a table format on the webpage
8. The user has the option to download the scraped data in CSV or JSON format by clicking on the respective download buttons
9. The user has the option to store the scraped data in a MongoDB database by clicking on the "Store Tweets" button
10. If the user chooses to store the data, the application converts the data to a dictionary format and inserts it into a "tweets" collection in the "twitter" database     in MongoDB
11. The application displays a success message if the data is stored successfully

# Execution
1. Install the necessary libraries: snscrape, pandas, pymongo, streamlit and base64 (terminal command-  pip install snscrape pandas pymongo streamlit ).
2. Create a MongoDB database with a "tweets" collection.
3. Copy and paste the code into a Python file named "twitter_scraping.py".
4. Run the file in a command prompt or terminal using the command "streamlit run twitter_scraping.py".
5. Access the webpage by clicking on the URL provided in the command prompt or terminal.
6. Instead of point 3, 4 and 5 you can install Visual Studio Code and give run, start debugging.  
7. Enter a keyword or hashtag, start and end date range, and tweet count limit.
8. Click on the "Scrape Tweets" button to initiate the scraping process.
9. View the scraped data in a table format on the webpage.
10. Click on the "Download CSV" or "Download JSON" button to export the scraped data in the respective format.
11. Click on the "Store Tweets" button to store the scraped data in the MongoDB database.
