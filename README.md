# Bookstore Scraper — Assignment 2

A Python web-scraping and bookstore-intelligence assignment using [Books to Scrape](https://books.toscrape.com/), a practice website.

## Features
- Scrapes book titles, prices, star ratings, availability, and product URLs.
- Uses Requests and Beautiful Soup to parse catalogue pages.
- Uses pandas to store and analyze the collected data.
- Produces a CSV dataset and a rating-count chart.
- Includes a £100 budget selection challenge using a 0/1 knapsack approach.

## Requirements
- Python 3.9 or newer
- Internet connection to access the practice website

Install dependencies:

```bash
python -m pip install -r requirements.txt
```

## Run
Run from the project directory:

```bash
python bookstore_scraper.py
```

To scrape a different number of catalogue pages (if supported by the script):

```bash
python bookstore_scraper.py --pages 5
```

The script writes the generated dataset and chart to its project directory.

## Project files
- `bookstore_scraper.py` — scraping and analysis script
- `competitor_books.csv` — collected book data
- `rating_counts.png` — chart of rating counts
- `assignment_answers.txt` — written assignment findings
- `requirements.txt` — Python dependencies

## Note
Books to Scrape is a demonstration website. Its prices and star ratings are randomly assigned and should not be interpreted as real market or customer data.
