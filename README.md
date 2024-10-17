# StockWatch

Welcome to **StockWatch**, a powerful API-driven application that provides real-time stock market insights using the RapidAPI platform. This project utilizes the Indian Stock Exchange API to fetch trending stocks, top gainers, and top losers, enabling users to stay updated with the latest market trends.

## Description

This is an API project utilizing RapidAPI, which serves as a marketplace for APIs. RapidAPI allows developers to connect to various APIs and manage them in one place. With StockWatch, users can easily access stock market data and trends, enhancing their investment decisions.

## Features

- Real-time trending stocks data
- Display of top gainers and top losers
- Responsive web interface
- Docker support for easy deployment

## Getting Started

### Option 1: Running with Docker
You can run this application easily using Docker. The Docker image is hosted on Docker Hub. Simply pull the image and run it:

1. Pull the Docker image:
   docker pull mayu1205/stockwatch
   
2. Run the Docker container:
    docker run -p 5000:5000 mayu1205/stockwatch

3. Access the application at http://localhost:5000.

### Option 2: Running Locally

Prerequisites

    Python 3.x
    RapidAPI key to access the Indian Stock Exchange API.

    Clone the repository:

    bash

1. git clone https://github.com/mayuri1205/stockwatch.git
cd stockwatch

2. Install the required packages:

3. pip install -r requirements.txt

4. Run the application:
   python app.py

5. Access the application at http://localhost:5000.

### API Endpoints

    /: Redirects to the trending stocks page.
    /trending: Fetches trending stocks data.
    /historical_data: Fetches historical stock data.
