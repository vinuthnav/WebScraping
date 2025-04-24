# Web Scraping Projects

This repository contains three distinct web scraping projects. Each project demonstrates how to scrape data from different websites, process it, and store it in a CSV file for further analysis. The projects covered in this repository are:

1. **Quotes Scraper**
2. **BBC News Scraper**
3. **Amazon Product Scraper**

## Project 1: Quotes Scraper

This project scrapes **quotes** from the website [quotes.toscrape.com](http://quotes.toscrape.com). It extracts the following details for each quote:
- Quote text
- Author
- Tags

### Features:
- Scrapes all pages of the site.
- Saves the scraped quotes to a CSV file for easy data manipulation and analysis.

### Libraries Used:
- `requests`
- `beautifulsoup4`
- `pandas`

### How to Run:
1. Clone the repository:
   git clone https://github.com/vinuthnav/WebScraping.git
2.Navigate to the project directory:
  cd WebScraping
3.Run the scraper:
  python quotes_scraper.py
4.The scraped quotes will be saved in quotes.csv


### Project 2:BBC news Headlines Scraper
Overview:
  This project scrapes news articles from the BBC News website. It collects the following information:
  Article title
  Article link
  Published date
### Libraries Used:
- `requests`
- `beautifulsoup4`
- `pandas`

### Features:
-  `Scrapes the latest news from the BBC News website.`
-  `Saves the scraped data in a structured CSV format.`

### How To Run:

1.Clone the repository:
  git clone https://github.com/vinuthnav/WebScraping.git
2.Navigate to the project directory:
  cd WebScraping
3.Run the scraper:
  python bbc_news_scraper.py
4.The scraped news articles will be saved in bbc_headlines.csv


### Project 3: Amazon Product Scraper:

### Overview:
  This project scrapes product details from the Amazon website. For each product, the following details are extracted:
  Product name
  Price
  Rating
  Number of reviews
  Product link
### Features:
  -`Scrapes product details using a list of product names.`
  -`Stores the scraped data in a CSV file.`
### Libraries Used:
  -`requests`
  -`beautifulsoup4`
  -`pandas`
### How To Run:

1.Clone the repository:
  git clone https://github.com/vinuthnav/WebScraping.git
2.Navigate to the project directory:
  cd WebScraping
3.Prepare an input CSV file with a list of product names (e.g., amazon_products.csv, amazon_products2.csv)
4.Run the scraper:
  python amazon_scraper.py
5.The scraped product data will be saved in amazon_products.csv,amazon_products2.csv


### Requirements
Each project uses the following Python libraries:
beautifulsoup4 for parsing HTML
requests for making HTTP requests
pandas for data manipulation
To install the required libraries, run:

pip install beautifulsoup4 requests pandas


### Notes:
Be cautious of scraping too frequently, as websites like Amazon and BBC News may block your IP for excessive requests.
Customize the code if you need to scrape additional details or handle different page structures.
Ensure your input files (e.g., product list for Amazon) are properly formatted.

### Vinuthna

### Key Sections:

1. **Project 1: Quotes Scraper**: Scrapes quotes from `quotes.toscrape.com`.
2. **Project 2: BBC News Scraper**: Scrapes news articles from BBC News.
3. **Project 3: Amazon Product Scraper**: Scrapes product details from Amazon.

### To Add This README to Your GitHub Repository:

1. **Create a file** named `README.md` in the root directory of your project.
2. **Paste the template** above into the `README.md` file.
3. **Commit** and **push** the file to your GitHub repository:

git add README.md
git commit -m "Add README file for WebScraping repository"
git pushContributing
Feel free to fork this repository, make improvements, and submit pull requests. Contributions are always welcome!

