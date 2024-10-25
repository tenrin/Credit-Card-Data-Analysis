# Credit Card Statement Analysis

## Project Overview

This project is designed to parse, clean, and analyze monthly credit card statements using Python. The primary goals include extracting transaction information, categorizing spending patterns, and preparing the data for further analysis.

The original transaction data was extracted from monthly PDF statements provided by **TD Bank**. While this project is tailored for the TD Bank statement format, similar techniques may work for statements from other banks with modifications.

> **Note:** To protect sensitive information, the credit card statement PDF files themselves are not included in this repository. Instead, a cleaned and processed version of the data is provided in CSV format. This file contains the extracted transaction data necessary for analysis.

## Files

- `data/transactions.csv`: Contains the cleaned and structured data extracted from the TD Bank statements.
- `scripts/`: Python scripts used for data extraction, parsing, and analysis.
- `LICENSE`: This project is licensed under the MIT License.

## Prerequisites

- Python 3.8 or higher
- Libraries: `pdfplumber`, `pandas`, `re`

## Usage

1. **Data Extraction**: The provided scripts demonstrate how to use `pdfplumber` to parse credit card statements.
2. **Data Processing**: Additional steps clean the data and save it as a CSV file for analysis.
3. **Data Analysis**: You can analyze the CSV file directly for insights into spending patterns, budgets, and other transaction-related metrics.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
