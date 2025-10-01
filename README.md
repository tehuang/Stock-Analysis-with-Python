# TWSE Stock P/E Filter

This Python script fetches daily stock data from the Taiwan Stock Exchange (TWSE) and filters stocks based on their Price-to-Earnings (P/E) ratio.

## Features
- Download daily stock data in CSV format from TWSE
- Convert messy CSV data into a clean pandas DataFrame
- Process numeric columns (remove commas, handle + / - signs)
- Filter stocks with P/E ratio between 0 and 15

## Prerequisites
- Python 3.8+
- Required Python packages:
```bash
pip install pandas numpy requests
