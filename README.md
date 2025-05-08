# Web Scraper for PChome and Costco Taiwan Website

This project is a Python-based web scraper designed to extract product information (name, price, and link) from the PChome 24h shopping website and the Costco Taiwan website.

## Overview

The script utilizes the Selenium library to automate web browser interactions, allowing it to navigate the websites, perform searches, and extract the desired data. It's configured to run in headless mode, meaning it operates without a visible browser window.

Currently, the script includes a function to fetch data specifically from the Costco Taiwan website for a given search term.

## Features

* **Search Functionality:** Allows users to search for specific products on both PChome and Costco.
* **Data Extraction:** Retrieves product names, prices, and product links.
* **Multiple Page Handling (Costco):** Navigates through the first 3 pages of search results on Costco.
* **Headless Browsing:** Operates in the background without opening a visible browser window.
* **Data Structuring:** Organizes the scraped data into a Pandas DataFrame for easy analysis and manipulation.

## Prerequisites

Before running the script, ensure you have the following installed:

* **Python 3.x**
* **pip** (Python package installer)

You will also need to install the necessary Python libraries:

```bash
pip install selenium pandas webdriver-manager
