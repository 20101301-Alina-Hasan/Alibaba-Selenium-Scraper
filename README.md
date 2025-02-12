# Alibaba Data Scraper 🏚️

This project is a web scraper built with Selenium to extract product information from Alibaba based on user-defined search queries. The scraper dynamically applies relevant filters based on the search input to refine the results.

## Features ✨

- Scrapes product name, price, company, MOQ (Minimum Order Quantity), rating, image link, and product link.
- Dynamically applies filters based on keywords in the user's search input.
- Supports pagination to scrape multiple pages of results.
- Excludes products with missing or invalid data.

---

## JavaScript Version 

### Requirements ⚙️

To run this project, you need to have the following installed:

- Node.js
- npm (Node Package Manager)
- Microsoft Edge 🌐 (for Selenium WebDriver)

### Installation 🔧

1. **Clone the repository** (if applicable):

   ```bash
   git clone https://github.com/20101301-Alina-Hasan/Alibaba-Selenium-Scraper.git
   cd Alibaba-Selenium-Scraper
   ```

2. **Install required Node.js packages**:

   ```bash
   npm install
   ```

### Usage 🚀

1. **Run the script**:

   ```bash
   node alibaba-selenium-scraper.js
   ```

2. **Input your search criteria**:
   
   - Enter the product you want to search for (e.g., "men's black t-shirt").
   - Enter the maximum price you want to filter by (e.g., "5").

3. **View the output**:
   - The scraped data will be saved or displayed as specified in your Node.js script 📊.

### Restrictions 🔍

Some added restrictions include:

- If the product name is nil, skip the product. 🚫
- If price is nil or given in a range, skip the product. 🚫
- If product link is nil, skip the product. 🚫
- If rating is nil, skip the product. 🚫
- If image link is nil, skip the product. 🚫

---

## Python Version 

### Requirements ⚙️

To run this project, you need to have the following installed:

- Python 3.x 🐍
- Microsoft Edge 🌐 (for Selenium WebDriver)

### Installation 🔧

1. **Clone the repository** (if applicable):

   ```bash
   git clone https://github.com/20101301-Alina-Hasan/Alibaba-Selenium-Scraper.git
   cd Alibaba-Selenium-Scraper
   ```

2. **Install required Python packages**:

   ```bash
   pip install selenium
   ```

### Usage 🚀

1. **Run the script**:

   ```bash
   python alibaba-selenium-scraper.py
   ```

2. **Input your search criteria**:
   
   - Enter the product you want to search for (e.g., "men's black t-shirt").
   - Enter the maximum price you want to filter by (e.g., "5").

3. **View the output**:
   - The scraped data will be saved in `alibaba_results.json` 📊.

### Restrictions 🔍

Some added restrictions include:

- If the product name is nil, skip the product. 🚫
- If price is nil, skip the product. 🚫
- If product link is nil, skip the product. 🚫
- If rating is nil, skip the product. 🚫
- If image link is nil, skip the product. 🚫

---

## Notes 📝

- Ensure that your selectors are up-to-date with Alibaba's current HTML structure.
- This scraper is applicable as of February 2025.
