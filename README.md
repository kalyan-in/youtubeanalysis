# youtubeanalysis

This project demonstrates how to collect and analyze trending video data from YouTube using Python. By leveraging the YouTube Data API v3, I have gathered data about the top trending videos in the US and perform exploratory data analysis (EDA) to uncover insights related to video engagement, categories, durations, and upload times.

Overview
In this project,

Collect Data: Retrieve details of the top trending videos on YouTube, including video IDs, titles, descriptions, publication dates, channel information, tags, durations (in ISO 8601 format), and engagement metrics (views, likes, comments, etc.).
Clean & Process Data: Convert raw data into usable formats (e.g., converting ISO 8601 durations to seconds and publication dates to datetime objects) for analysis.
Explore & Visualize: Use Pandas, Matplotlib, and Seaborn to generate histograms, scatter plots, and bar charts. This helps identify patterns such as which video categories perform best, how video length impacts engagement, and the optimal times for uploading videos.
Draw Insights: Analyze the data to answer questions like:
Which video categories attract the highest engagement?
How does video length influence view counts?
What are the best upload times to maximize views?

Project Structure:
data_collection.py: Script to collect trending video data using the YouTube Data API v3.
data_analysis.py: Script to clean, analyze, and visualize the collected data.
trending_videos.csv: CSV file containing the collected data.

Usage
Data Collection Script: Connects to the YouTube Data API, collects trending video details, and saves them to a CSV file.
Data Analysis Script:
Converts data types (e.g., publication dates to datetime, durations to seconds).
Generates visualizations such as histograms for views, likes, and comments, scatter plots for relationships (e.g., video length vs view count), and bar charts for category analysis.
Extracts key insights like the optimal video length and best upload times.

