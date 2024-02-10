# Google Maps Data Extractor
## Overview

The Google Maps Data Extractor is a Python application that automates the process of extracting information from Google Maps. It allows users to search for specific keywords in combination with locations, scraping details about businesses or places matching the criteria.

## Features

User-Friendly Interface: The application provides a graphical user interface (GUI) using the Tkinter library, making it easy for users to interact with the tool.

Scraping Capability: The tool scrapes data from Google Maps, including business name, address, department, phone number, URL, ratings, total reviews, available timings, and email ID.

Multi-Threading: The application uses multi-threading to improve efficiency. Each keyword-location combination runs as a separate thread, allowing for concurrent data extraction.

Real-time Updates: The GUI displays real-time updates on the scraping progress, such as the total data count and the current status.

Download Results: Users can download the scraped data in an Excel (.xlsx) format, providing a convenient way to store and analyze the extracted information.

## How to Use

### Keywords and Locations:

Enter keywords and locations in the respective entry fields.
Separate multiple keywords and locations with commas.
Start Scraping:

Click the "START" button to initiate the scraping process.
The tool will search Google Maps for the specified combinations and extract relevant data.
Stop Scraping:

Click the "STOP" button to halt the scraping process at any time.
The application will update the status accordingly.
Download Results:

Click the "DOWNLOAD" button to save the scraped data to an Excel file.
Choose the destination for the file.

## Dependencies
- Python 3.x
- Tkinter (included in standard Python libraries)
- Selenium
- Pandas
- Requests
- Openpyxl
- Webdriver_manager
