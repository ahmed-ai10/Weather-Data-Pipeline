# Weather Data Pipeline

## Overview
![Weather Data Pipeline](images/weather-pipeline.png)

An end-to-end data pipeline that collects weather data from an API, validates and transforms it using Python and Pandas, and stores the processed data in PostgreSQL.

## Pipeline

Weather API
↓
Python / Requests
↓
Validation & Transformation
↓
PostgreSQL

## Technologies
- Python
- Requests
- Pandas
- PostgreSQL

## Key Features
- Fetch weather data from an external API
- Validate and transform incoming data
- Store structured data in PostgreSQL
- Prepare data for future analysis

## Project Structure

```text
weather-data-pipeline/
│
├── src/
│   └── Data Pipeline.ipynb
├── requirements.txt
├── README.md
└── .gitignore
