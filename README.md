How to Use
1. Command Line Input
Run with a search term and optional max results:

bash
Copy
Edit
python script.py -s "Restaurants in New York" -t 20
2. Input File
Create an input.txt with one search query per line:

sql
Copy
Edit
Restaurants in New York
Cafes in Los Angeles
Then run:

bash
Copy
Edit
python script.py
Output
Data saved in output/ as:

google_maps_data_<search_term>.xlsx

google_maps_data_<search_term>.csv

Requirements
bash
Copy
Edit
pip install playwright pandas openpyxl
playwright install
Notes
Script opens a visible browser.

Scraping limits may apply.

Interface changes may break the script.
