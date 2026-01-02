# Form Filler Automation

## What it does
This Python script automatically fills out a web form using data from a CSV file.  
It reads each row and submits the form automatically using Selenium.

## How to use

1. Install required libraries:
```bash
pip install pandas selenium

2. Download ChromeDriver and note its path: https://sites.google.com/chromium.org/driver/

3. Prepare your form_data.csv with columns matching the form fields:

4. Update CHROMEDRIVER_PATH in form_filler.py with your ChromeDriver path.

5. Update form_url with the URL of the form you want to automate.

6. Run the script:
python form_filler.py

Tools Used
Python
Pandas
Selenium
ChromeDriver
