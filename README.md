# Project_1

PRICEBOT: Revolutionizing Short-Term Rental Pricing

Introducing PRICEBOT, an innovative tool designed to optimize pricing for short-term rentals. By leveraging platform insights and advanced data analysis, PRICEBOT empowers hosts to maximize profitability and occupancy rates.

Project Overview: The PRICEBOT Journey

- Step 1: Scraping
  Collect raw data from short-term rental platforms using scraping techniques on Python – Beautiful Soup then Selenium

- Step 2: Cleaning
  Process and refine the scraped data to ensure accuracy and reliability.

- Step 3: Analysis
  Perform in-depth exploratory data analysis to uncover pricing trends vs actual properties.

Data Wrangling Challenges

- Data Preservation
  Challenge: Avoiding data corruption during cleaning. Solution: Create backups of raw data. (Now Pricebot stores every run: both raw   and clean data with timestamps, useful for trends over time!)

- Scraping Technique
  Challenge: Ineffective results with BeautifulSoup. Solution: Switch to Selenium for improved data extraction.

- Overall - Iterative Refinement
  Challenge: Multiple failed runs. Solution: Continuous code improvement and persistence.

Exploratory Data Analysis

- Descriptive Statistics
  Analyze Average Daily Rates (ADR) for each month to identify the seasonal trend and the actual price distribution.

- Quartile Analysis
  Use median (percentile 50) vs. mean to mitigate the impact of outliers on pricing strategies.

- Market Benchmarking
  Compare real properties against market ADRs to identify pricing opportunities.
























