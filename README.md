# Largest US Companies by Revenue (2023)

This project involves web scraping to compile a list of the largest companies in the United States by revenue as of 2023. The data is sourced from the Fortune 500 list and Forbes. The scraped data is organized into a Pandas DataFrame and can be exported to a CSV file.

## Project Description

The Fortune 500 list of companies includes only publicly traded companies, including tax inversion companies, as well as corporations with a foundation in the United States, such as corporate headquarters, operational headquarters, and independent subsidiaries. The list excludes large privately held companies such as Cargill and Koch Industries, whose financial data is not necessarily available to the public. However, it includes several government-sponsored enterprises that were created by acts of Congress and later became publicly traded.

### Features

- Scrapes the largest companies in the United States by revenue.
- Compiles data from the Fortune 500 list and Forbes.
- Organizes the data into a Pandas DataFrame.
- Exports the DataFrame to a CSV file.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repo.git
    cd your-repo
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Ensure you have all the dependencies installed.
2. Run the web scraping script:
    ```bash
    python scrape_companies.py
    ```

3. After the script runs, the data will be saved to a CSV file in the project directory.

## Project Structure

- `scrape_companies.py`: The main script for web scraping.
- `requirements.txt`: List of dependencies required for the project.
- `README.md`: Project description and instructions.

## Dependencies

- pandas
- requests
- beautifulsoup4

You can install the dependencies using:
```bash
pip install -r requirements.txt
