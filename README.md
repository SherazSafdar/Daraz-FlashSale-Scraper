# Daraz Flash Sale Scraper 🌟

Unearth hidden gems during Daraz's flash sales with this Python web scraping project! The scraper dynamically scrolls through the flash sale section, capturing product details, and organizes them for analysis using Pandas. Shop smarter and discover unbeatable deals!

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is a Python web scraper built with Selenium to scrape product details from the Daraz website's flash sale section. By automating the scrolling process and data extraction, you can easily access product names, discounted prices, original prices, and any available discounts. With the data neatly organized in a Pandas DataFrame, you can analyze and visualize the deals to make informed purchasing decisions.

## Features

- Automates web scraping process using Selenium.
- Dynamically scrolls through the flash sale section to load all products.
- Extracts product names, discounted prices, original prices, and discounts (if applicable).
- Organizes data in a structured Pandas DataFrame for easy analysis.
- Provides valuable insights into pricing trends and discounts.

## Requirements

To run this project, you need the following:

- Python 3
- Selenium
- Pandas
- Web driver (e.g., Firefox driver for this example)

## Installation

1. Clone this repository to your local machine.
2. Install the required dependencies using pip:
pip install selenium pandas

markdown
Copy code

## Usage

1. Ensure you have the required web driver (e.g., Firefox driver) installed and added to your system PATH.
2. Run the `daraz_flashsale_scraper.py` script:
python daraz_flashsale_scraper.py

yaml
Copy code
3. Sit back and watch as the scraper dynamically scrolls through the flash sale section and collects product details.
4. The scraped data will be saved in a CSV file named "product_details.csv" in the current working directory.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Happy scraping and shopping! If you have any questions or need assistance, please don't hesitate to reach out. Enjoy uncovering amazing deals with this Daraz Flash Sale Scraper! 🛍️💎