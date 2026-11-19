# hclproject_weather_track_analysis
# Interactive State CSV Data Viewer

A simple Python script using the `pandas` library that allows users to dynamically select a state-specific CSV dataset and preview a custom number of rows.

## Features
* **Interactive File Selection:** Prompts the user to choose from a list of available state CSV files (`delhi.csv`, `maharstra.csv`, `punajb.csv`, `uttar pradesh.csv`).
* **Custom Data Preview:** Lets the user specify exact row counts (`n`) to inspect the top records of the chosen dataset.
* **Colab & Jupyter Ready:** Designed to run smoothly in interactive notebook environments like Google Colab.

## Prerequisites
Make sure you have Python installed along with the `pandas` library:

```bash
pip install pandas
```

## Project Structure
Ensure your CSV datasets are placed in the same root directory (or uploaded to your Colab session storage) before running the script:

```text
├── delhi.csv
├── maharstra.csv
├── punajb.csv
├── uttar pradesh.csv
└── analysis.ipynb
```

## Usage
1. Run the Python cell or script.
2. When prompted, enter the exact filename from the available options (e.g., `delhi.csv`).
3. Enter the number of rows you wish to display.

### Example Output
```text
Following State(file_name) Are Available delhi.csv ,maharstra.csv ,punajb.csv ,uttar pradesh.csv
Enter the CSV file name: delhi.csv
How many rows do you want to see? 5
Here are the first 5 rows:
   Column1  Column2  Column3
0      ...      ...      ...
```

## Note on Filenames
Please note that the script expects the exact spelling of the files as listed in the prompt (`maharstra.csv` and `punajb.csv`). If you rename your files to standard spellings, be sure to update the print prompt in the code accordingly.
