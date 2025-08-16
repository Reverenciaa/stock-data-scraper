# Stock Data Scraper

This project is a Python-based scraper for fetching stock and cryptocurrency historical data. It uses web scraping and the `yfinance` library to collect and save data for selected symbols.

## Features
- Scrapes historical stock data from stockanalysis.com
- Scrapes historical crypto data from coinlore.com
- Fetches chart data for stocks and cryptos using Yahoo Finance
- Saves data to CSV files for further analysis

## Requirements
- Python 3.7+
- Packages: `requests`, `yfinance`, `beautifulsoup4`, `pandas`

## Usage
1. Install dependencies:
   ```bash
   pip install requests yfinance beautifulsoup4 pandas
   ```
2. Run the scraper:
   ```bash
   python data.py
   ```
3. Output CSV files will be saved in the `stockprediction` folder.

## Project Structure
- `data.py`: Main scraper script
- `stockprediction/`: Output data folder

## Future Improvements
- Add a backend API (Flask/FastAPI) for integration with a React frontend
- Add more symbols and data sources
- Dockerize the app for easy deployment

## License
MIT
