# Youtube Data Harvesting and Warehousing.

## Introduction:

YouTube Harvesting is a tool designed to gather data from YouTube, specifically focusing on extracting information from videos, channels, and user activities. This README file provides an overview of the tool, its features, installation instructions, usage guidelines, and other relevant information.

### Tools

* Virtual code.
* Jupyter notebook.
* Python 3.11.0 or higher.
* MySQL.
* MongoDB.
* Youtube API key.

### Import Libraries

**Youtube API libraries**
* import googleapiclient.discovery
* from googleapiclient.discovery import build

**File handling libraries**
* import json
* import re

**MongoDB**
* import pymongo

**SQL libraries**
* import mysql.connector
* import sqlalchemy
* from sqlalchemy import create_engine
* import pymysql

**pandas, numpy**
* import pandas as pd
* import numpy as np

**Dash board libraries**
* import streamlit as st
* import plotly.express as px

## Features:

YouTube Harvesting offers the following key features:

1. Video Data Extraction: Extracts information such as title, description, duration, view count, like count, dislike count, and comment count from YouTube videos.
2. Channel Data Extraction: Retrieves data about a YouTube channel, including its title, description, subscriber count, view count, and video count.
3. User Activity Monitoring: Tracks the activities of YouTube users, including likes, dislikes, comments, and subscriptions, and provides relevant data.
4. Search Functionality: Allows searching for videos and channels based on keywords, tags, or specific criteria.
5. Data Export: Enables exporting the extracted data in various formats, such as CSV, JSON, or Excel, for further analysis.

## Installation

To install YouTube Harvesting, follow these steps:

* pip install google-api-python-client, pymongo, mysql-connector-python, sqlalchemy, pymysql, pymysql, pandas, numpy, 
  plotly-express, streamlit.
  
 ( pip install google-api-python-client pymongo mysql-connector-python sqlalchemy pymysql pandas numpy plotly-express streamlit )
 
Clone the GitHub repository: git clone https://github.com/yourrepository/youtubeharvesting.git
Navigate to the project directory: cd youtubeharvesting
Install the required dependencies: pip install -r requirements.txt
Usage
Obtain a YouTube Data API key from the Google Developers Console.
Set the API key in the configuration file or provide it as an argument when running the tool.
Use the provided command-line interface (CLI) or import the library into your own Python scripts.
Refer to the documentation for detailed instructions on each feature and their respective usage.
Configuration
The configuration file allows customization of various aspects of YouTube Harvesting. Modify the config.yaml file to adjust settings such as API key, output format, and logging preferences.
