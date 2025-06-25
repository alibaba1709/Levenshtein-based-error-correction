# Levenshtein based error correction

This project reads raw survey data containing career aspirations (including spelling errors), automatically corrects them using a Levenshtein distance–based algorithm, and visualizes the cleaned data in a bar chart.

## Features

- Reads career responses from a CSV file
- Corrects misspelled entries by matching to a predefined list of valid careers
- Visualizes the frequency distribution of career aspirations using a bar graph

## How to Use

1. Open the `main.ipynb` notebook using Jupyter Notebook or any other compatible environment.
2. Ensure the input file (`career choices.csv`) is placed in the same directory or update the file path inside the notebook.
3. Run all cells in the notebook to:
   - Automatically correct misspelled career responses.
   - Generate and display a bar chart of cleaned career aspirations.


## Career Options Used for Matching

- Doctor
- Engineer
- Teacher
- Lawyer
- Accountant
- Nurse
- Police
- Architect
- Dentist
- Pharmacist

## Notes

- The script does not save or display the corrected text data.
- Input file should contain career responses in the first column.

## Author

**Vanshdeep**  
Development Period: May 2024
