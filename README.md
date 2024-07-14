# Amazon Web Scraping Project: MacBook Air M2 Price, Ratings, and Date

## Project Overview

This project is designed to scrape and track the daily price, ratings, and date for the MacBook Air M2 on Amazon using Python. The collected data will be stored in a CSV file for further analysis and monitoring.

## Features

- Scrapes the current price of the MacBook Air M2.
- Scrapes the ratings for the product.
- Records the date of each scrape.
- Stores the scraped data in a CSV file.
- Is sheduled to record the data daily.
- Will send an Email when price dops below 999$.

## Prerequisites

Before running this project, ensure you have the following installed:

- Python 3.0+
- Jupyter Notebook
- Required Python libraries (see below)

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/ARSIBR/Amazon-Web-Scrapper
    cd amazon-web-scraping-macbook-air-m2
    ```

2. Install the required Python libraries:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Update the `config.py` file with the URL of the MacBook Air M2 product page on Amazon.

2. Run the scraper script:

    ```bash
    python scraper.py
    ```

3. The scraped data will be saved in a CSV file named `Amazon_Web_Scrapper_Macbook.csv` in the project directory.
