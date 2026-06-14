# Excel Data Cleaner

A lightweight Python script for cleaning messy Excel and CSV files. Designed for quick, repeatable data preparation tasks.

## Features

- Removes duplicate rows
- Removes completely empty rows
- Trims extra whitespace from text columns
- Standardizes column names (lowercase, underscores instead of spaces)
- Exports a clean, ready-to-use Excel file
## Requirements

- Python 3.x
- pandas

Install dependencies:
pip install pandas openpyxl

## Usage

1. Place your input file (.csv or .xlsx) in the same directory as the script.
2. Update the INPUT_FILE variable with your file's name.
3. Run the script:
python excel_data_cleaner.py
4. The cleaned file will be saved as cleaned_output.xlsx.## Example

Before: Inconsistent column names, duplicate entries, blank rows, extra spaces.

After: Clean column headers, no duplicates, no empty rows, trimmed text.

## Author

Available for freelance data cleaning and automation projects on Fiverr.