Introduction

YouTube Data Harvesting and Warehousing is a project aimed at developing a user-friendly Streamlit application that leverages the power of the Google API to extract valuable information from YouTube channels. The extracted data is then stored in a MongoDB database, subsequently migrated to a SQL data warehouse, and made accessible for analysis and exploration within the Streamlit app.

Contents

Key Skills
Installation
Usage
Features
Retrieving data from the YouTube API
Storing data in MongoDB
Migrating data to a SQL data warehouse
Data Analysis

Features

  Retrieve data from the YouTube API, including channel information,videos, and comments.
  Store the retrieved data in a MongoDB database.
  Migrate the data to a MySQL data warehouse.
  Analyze and visualize data using Streamlit.
  Perform queries on the MySQL data warehouse.
  Display the answers for the queries.

Retrieving data from the YouTube API

 The project utilizes the Google API to retrieve comprehensive data from YouTube channels. The data includes information on channels, playlists, videos, and comments.

Storing data in MongoDB

 The retrieved data is stored in a MongoDB database based on channel info.

Migrating data to a MySQL data warehouse

The application allows users to migrate data from MongoDB to a MySQL data warehouse. Users can given the input as channel id to migrate the data to Mysql database. To ensure compatibility with a structured format, the data is cleansed using the powerful pandas library. Following data cleaning, the information is segregated into separate tables, including channels, videos, and comments, utilizing MySQL queries.

Analysis

The project provides comprehensive data analysis capabilities using Streamlit.

Conclusion

This project leverages the Google API to collect, store, and analyze data from YouTube channels, making it accessible through a user-friendly Streamlit application. With MongoDB for initial storage and MySQL for structured data warehousing, users can seamlessly transition and explore data.
