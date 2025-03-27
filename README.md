# Image Scraper

## Overview
This project is an image scraper that extracts images from a specified website using Selenium and BeautifulSoup. The scraped images can be downloaded and stored locally for further analysis.

## Features
- Uses Selenium WebDriver to navigate websites.
- Extracts image URLs using BeautifulSoup.
- Downloads and stores images automatically.
- Saves extracted data in a structured format using Pandas.

## Technologies Used
- Python
- Selenium
- BeautifulSoup
- Pandas
- Requests

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/image-scraper.git
   cd image-scraper
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Download the appropriate Chrome WebDriver and update the executable path in the script.

## Usage

1. Run the script:
   ```sh
   python img_scraper.py
   ```
2. The script will navigate to the target website and download images into a specified folder.

## Example Output
- Extracted image URLs stored in a CSV file.
- Images downloaded and saved locally.

## Notes
- Ensure that the Chrome WebDriver version matches your installed Chrome version.
- Modify the target URL and output directory in the script as needed.

## Conclusion

This project provides an automated way to scrape and download images from websites efficiently. It can be extended further to handle dynamic content, apply filters, or integrate with cloud storage solutions. By leveraging Selenium and BeautifulSoup, this scraper is a useful tool for data collection and research purposes.
