# YouTube-Data-Harvesting-
YouTube Data Harvesting and Warehousing using VS Code,PostgreSQL, MongoDB, and Streamlit 

# Overview

      This project is focused on harvesting data from YouTube channels using the YouTube API, processing the data, and warehousing it. The harvested data is initially stored locally in a MongoDB database as documents and is then converted into SQL records for in-depth data analysis. The project's core functionality relies on the Extract, Transform, Load (ETL) process.

# Approach 
    Harvest YouTube channel data using the YouTube API by providing a 'Channel ID'.
    Store channel data locally in MongoDB as documents.
    Convert MongoDB data into local SQL records for data analysis.
    Use 11 different methods within the "YT2SQL" class to perform various tasks.
    Implement Streamlit to present code and data in a user-friendly UI.
    Execute data analysis using SQL queries and Python integration.

# Getting Started

    Install/Import the necessary modules: Streamlit, Pandas, PyMongo, Psycopg2, Googleapiclient, and Isodate.
    Ensure you have access to a local MongoDB instance and set up a local PostgresSQL DBMS on your environment.

# Technical Steps to Execute the Project

### Step 1: Install/Import Modules

    Ensure the required Python modules are installed: Streamlit, Pandas, PyMongo, Psycopg2, Googleapiclient, and Isodate.

### Step 2: Utilize the "YT2SQL" Class

    There are 11 methods within the class, each with specific functionality for data extraction and transformation. These methods cover tasks like data retrieval, data storage, and data analysis.

### Step 3: Run the Project with Streamlit

    Open the command prompt in the directory where "YtAPiproject.py" is located.
    Execute the command: streamlit run YtAPiproject.py. This will open a web browser, such as Google Chrome, displaying the project's user interface.

### Step 4: Configure Databases

    Ensure that you are connected to both the local MongoDB instance and your local PostgresSQL DBMS.

### Methods

    Get YouTube Channel Data: Fetches YouTube channel data using a Channel ID and creates channel details in JSON format.
    Get Playlist Videos: Retrieves all video IDs for a provided playlist ID.
    Get Video and Comment Details: Returns video and comment details for the given video IDs.
    Get All Channel Details: Provides channel, video, and playlist details in JSON format.
    Merge Channel Data: Combines channel details, video details, and playlist details into a single JSON format.
    Insert Data into MongoDB: Inserts channel data into the local MongoDB as a document.
    Get Channel Names from MongoDB: Retrieves channel names from MongoDB documents.
    Convert MongoDB Document to Dataframe: Fetches MongoDB documents and converts them into dataframes for local SQL data insertion.
    Data Transformation for SQL: Performs data transformation for loading into local SQL.
    Data Load to SQL: Loads data into local SQL.
    Data Analysis: Conducts data analysis using SQL queries and Python integration.
    Manage MongoDB Documents: Manages MongoDB documents with various options.
    Delete SQL Records: Deletes local SQL records related to the provided YouTube channel data with various options.

# Skills Covered

    Python (Scripting)
    Data Collection
    MongoDB
    SQL
    API Integration
    Data Management using local MongoDB and local PostgreSQL
    IDE: VS Code



