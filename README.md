# Tesla and GameStop Stock Price and Revenue Data Analysis

This project focuses on the analysis of Tesla and GameStom historical stock prices and revenue data.
Using web scraping techniques, we collect Tesla's revenue from an online source and use Yahoo Finance (yfinance) to fetch stock price data.
The project visualizes the historical share price and revenue trends, presenting the data in an easy-to-interpret graph.

## Project Overview

### Objective

The goal of this project is to scrape Tesla's and GameStop's revenue data, retrieve historical stock prices, and visualize both metrics in a single plot to observe trends over time.

### Libraries

 - **Pandas:** Used for data manipulation and cleaning
 - **Plotly:** Library for creating interactive visualizations and subplots.
 - **BeatifulSoup:** For web scraping Tesla's and GameStop'S revenue data from the web.
 - **yfinance:** Fetches Tesla’s and GameStop's historical stock data.
 - **Requests:** To handle HTTP requests and retrieve web page content.

## Features

 - **Web Scraping:** Using BeautifulSoup, the project scrapes Tesla's revenue data from a provided online source.
 - **Stock Price Data Fetching:** The historical stock prices for Tesla are retrieved using the yfinance library.
 - **Data Cleaning:** Cleaning the scraped revenue data to remove unwanted characters (e.g., commas, dollar signs) and converting it into a usable format.
 - **Data Visualization:** Tesla and GameStop graphify and visualize.


Note: This project is the final assigment project of the IBM python project for data science course from coursera.
