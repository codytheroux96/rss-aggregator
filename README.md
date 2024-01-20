# RSS Aggregator

## Description
A live server and RSS aggregator built with Golang and PostgreSQL. Users can subscribe to different RSS feeds via that websites URL and using Go Channels, the RSS aggregator will scrape the feeds from these websites every 60 seconds (can be adjusted) and display all of the different RSS feeds available and their contents. This project takes security precautions by generating a random API key for every user as well as utilizing CORS. 

## Technologies
- Go(Golang)
- PostgreSQL
- SQLc
- Goose
- CORS

## Installation and Prerequisites
- You will need Go(Golang) installed on your machine
- You will need PostgreSQL downloaded and it would be advantageous to download PGAdmin as well
- You will need a HTTP client to make your HTTP requests
- Once these are downloaded, clone this repository and then cd into it

## Usage
