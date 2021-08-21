# Table Creator

## [](https://github.com/MadsCapstone/tableCreator#what-it-does)What it does?

The main purpose of this repository is to read the original source data files, consisting of proprietary NOAA data (do not share) and USGS geojson data, and convert them into tabular data to be uploaded into the database.  The script downloads the public technical memorandum pdf files from NOAA's website and extracts the relevant text, creates classifiers to classify the text and exports an Excel file to be sent to NOAA.  The script combines this data with food-web data and geojson data to create networks, and then stores this data to files for use with the visualizations.

## [](https://github.com/MadsCapstone/tableCreator#how-to-use-this-repository)How to use this repository?

1.  Download the notebook for use in Google Colabs 
or
2.  Connect directly to the notebook with this link:
https://colab.research.google.com/drive/1LJh4JjD8g71bO-RyA3OyJWRU3dxj3yjx?authuser=1
(do not share the proprietary data in the drive)

## [](https://github.com/MadsCapstone/tableCreator#future-of-this-repository)Future of this repository

-   Likely only going to be used to generate data for the db
-   Can be used in conjunction with Jupyter Dash to deliver the Ripple Visualization