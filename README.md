\# London School File Filtering



This repository contains a simple Python workflow for filtering school performance files and keeping only records for London schools.



\## Project purpose



The notebook uses a list of London school URNs from an Excel file and applies this list to all files in a folder. It keeps only the rows where the `URN` belongs to a London school and saves the filtered results to a new output folder.



\## Main file



\- `notebooks/filter\_london\_school\_files.ipynb`



\## What this project demonstrates



This project demonstrates basic Python data handling skills, including:



\- reading Excel and CSV files with `pandas`

\- cleaning column names

\- checking whether required columns exist

\- converting variables to a consistent type

\- filtering data based on a key variable

\- writing a reusable processing function

\- looping through multiple files in a folder

\- handling errors with `try/except`



\## Input files



Place the following in the `data/` folder:



1\. `London\_school\_info.xlsx`

&#x20;  - must contain a column called `URN`



2\. `performance\_2025/`

&#x20;  - this folder should contain the CSV or Excel files to be filtered

&#x20;  - each file must contain a column called `URN`



\## Output



The notebook creates:



\- `output/2025\_London/`



This folder will contain filtered versions of the original files, including only London school rows.



\## Software



This project uses Python and `pandas`.



See `requirements.txt` for package requirements.



\## Note on data



The original research data are not included in this repository because they may be confidential or restricted.

