# Virginia Tech Faculty Web Scraper

## Project Overview

Developed a Python web scraper to collect faculty information from three Virginia Tech departments: Business Information Technology, Finance, and Marketing.

The program automates faculty profile discovery, validates URLs, extracts faculty information, handles missing data, and exports the results into a structured CSV dataset.

This project was originally developed for BIT 3474: Data Management and Business Analytics at Virginia Tech.

## Technologies Used

- Python
- BeautifulSoup
- Requests
- Pandas
- Google Colab
- CSV

## Project Features

- **Automated Web Scraping:** Collects faculty information from three Virginia Tech department directories.
- **URL Validation:** Uses HTTP status checks to identify accessible faculty profile pages.
- **Data Extraction:** Extracts faculty names, titles, departments, colleges, and office locations.
- **Missing Data Handling:** Uses fallback values when information is unavailable.
- **Data Organization:** Structures the extracted information into a Pandas DataFrame.
- **CSV Export:** Exports faculty data into a CSV file with automatically generated unique IDs.

## Project Files

- **Python Script (.py):** Contains the web scraping and data processing code.
- **Google Colab Notebook (.ipynb):** Provides the original notebook containing the project code.
- **CSV Dataset (.csv):** Contains the collected faculty information in a structured format.

## How to Run

1. Download or open the Google Colab notebook.
2. Install the required Python libraries if they are not already available.
3. Run the notebook cells in order.
4. The program retrieves faculty information from the configured Virginia Tech directories.
5. Once processing is complete, the program exports the results to `omkorat_web_scraping.csv`.

*Note: The scraper depends on the structure and availability of Virginia Tech's faculty websites. Changes to those websites may require updates to the code.*

## Future Improvements

- Expand data cleaning and validation.
- Integrate SQL for database storage and queries.
- Develop visualizations for faculty data analysis.
- Improve error handling and automation.
