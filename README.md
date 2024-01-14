# YouTube_Data_Harvesting_and_Warehousing

The purpose of this project is to create an Streamlit app that pulls data about a YouTube channel from the Google API, stores it in a MongoDB database, moves it to a SQL data warehouse, and then lets users perform searches for channel details and join tables to view the data.


## Tools and libraries used for this project :
1. **Python** - Programming Language
2. **pymongo** - Python Framework that helps in connecting with MongoDB
3. **pandas** - Python Library for Data Visualization
4. **streamlit** - Python framework to rapidly build and share beautiful machine learning and data science web apps
5. **google-api-python-client** - Python Library that offers simple, flexible access to many Google APIs.
6. **mysql-connector-python** - Python Library that enables Python programs to access MySQL databases


## Project Workflow
1. Enter a YouTube channel ID in the input field and click the "Retrieving data" button.
   
3. The app will retrieve the channel details like  Channel_id, Channel_name Playlist_id, Subscribers, Views, Total_videos, Description and so on.

4. Now to upload the data to MongoDB Atlas Database Cluster, click the "Enter data". The app will show a success message after the data is been uploaded successfully.
   
5. After the data gets uploded to MongoDB Atlas, now from the top to select the Migrate tab.  Now select the channel whose data you want to migrate to the SQL database from the dropdown menu.
   
6. Then click the "Migrate Data" button to migrate the selected channel data to SQL Database.

7. The app will display a success message once the data has been migrated.
   
8. Now from the top select the "Query Data" and browse through the dropdown menu and select the Query questions.
    
9. According to the selected statement the data will be queried from the SQL Database  and will be displayed here on the screen in the streamlit application.

## Conclusion
This project aims to develop a user-friendly Streamlit application that utilizes the Google API to extract information on a YouTube channel, stores it in a MongoDB database, migrates it to a SQL data warehouse, and enables users to search for channel details and join tables to view data in the Streamlit app.
