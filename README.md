# Cretivox Client List Web Scraper

This repository contains a web scraping project that extracts the list of clients from the Cretivox website using Selenium. The extracted data is saved into a CSV file for easy access and analysis. The project is designed to work in a Jupyter Notebook environment, allowing for interactive data extraction and transformation.

## Project Overview

This project aims to:
- Collect client data from [Cretivox's Work page](https://cretivox.com/work).
- Transform the scraped data into a structured CSV format.
- Provide reusable code and steps to adapt or expand this web scraping workflow for similar projects.

## Features

- **Automated Web Scraping**: Uses Selenium to automate data extraction from dynamic web elements.
- **Data Storage in CSV Format**: Exports the scraped data into a CSV file, making it easy to analyze and share.
- **Reusable Code**: The Jupyter Notebook format allows for interactive execution and modification.

## Requirements

- Python 3.x
- Jupyter Notebook
- [Selenium](https://pypi.org/project/selenium/)
- [Pandas](https://pandas.pydata.org/)
- Chrome WebDriver (compatible with your Chrome browser version)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/username/cretivox-client-scraper.git
   ```
2. Install required libraries:
   ```bash
   pip install selenium pandas webdriver-manager
   ```
3. Download the [Chrome WebDriver](https://chromedriver.chromium.org/downloads) and ensure it's in your PATH, or set up the driver path in the script.

## Usage

1. Open the Jupyter Notebook in Visual Studio Code or Jupyter Lab.
2. Run each cell in sequence to:
   - Initialize the web driver.
   - Access the Cretivox Work page.
   - Scrape client data based on the specified class name (`clientList_list__BCNJn`).
   - Save the data to a CSV file (`client_list.csv`).

3. After running, check the generated `client_list.csv` file in your working directory.

## Example Output

The `client_list.csv` file will contain the following structure:

| Client Name       |
|-------------------|
| Client 1          |
| Client 2          |
| ...               |

## Notes

- This script is configured for Chrome; adjust if using a different browser.
- Use caution and follow [Cretivox's Terms of Service](https://cretivox.com) regarding data scraping.

## Contributing

Contributions are welcome! If you find an issue or have suggestions, feel free to create an issue or submit a pull request.
