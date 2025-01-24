# Alibaba Price Comparison Scraper

This project is a web scraper built with Selenium to extract product information from Alibaba based on user-defined search queries and filters. The scraper dynamically applies relevant filters based on the search input to refine the results.

## Features

- Scrapes product name, price, company, MOQ (Minimum Order Quantity), rating, image link, and product link.
- Dynamically applies filters based on keywords in the user's search input.
- Supports pagination to scrape multiple pages of results.
- Excludes products with missing or invalid data.

## Requirements

To run this project, you need to have the following installed:

- Python 3.x
- Selenium library
- Microsoft Edge WebDriver (compatible with your Edge browser version)

### Installation

1. **Clone the repository** (if applicable):

   ```bash
   git clone https://github.com/20101301-Alina-Hasan/Alibaba-Selenium-Scraper.git
   cd Alibaba-Selenium-Scraper
   ```

2. **Install required Python packages**:

   ```bash
   pip install selenium
   ```

3. **Download Microsoft Edge WebDriver**:
   - Ensure you have Microsoft Edge WebDriver installed and available in your system PATH. You can download it from [Microsoft Edge WebDriver](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/).

## Usage

1. **Run the script**:

   ```bash
   python alibaba-selenium-scraper.py
   ```

2. **Input your search criteria**:

   - Enter the product you want to search for (e.g., "men's black t-shirt").
   - Enter the maximum price you want to filter by.

3. **View the output**:
   - The scraped data will be saved in `alibaba_results.json`.

## Optimizations

We can optimize this further by adding some restrictions:

1. If the product name is nil, we can skip the product.
2. If price is nil, we can skip the product.
3. If product link is nil, we can skip the product.
4. If rating is nil, we can skip the product.
5. If image link is nil, we can skip the product.
6. If price is given in a range, we can skip the product.
7. Add more than one filter option (Optional).

## Notes

- Ensure that your selectors are up-to-date with Alibaba's current HTML structure.
