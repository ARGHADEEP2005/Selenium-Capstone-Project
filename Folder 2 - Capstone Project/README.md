# Capstone Project - Selenium WebDriver Automation

## Project Overview

This Capstone Project demonstrates web application automation using Selenium WebDriver with Python and PyTest.

The project automates an e-commerce workflow including login, product search, adding a product to the cart, updating the quantity, and verifying cart details.

## Technologies Used

- Python
- Selenium WebDriver
- PyTest
- pytest-html
- HTML
- Google Chrome

## Application Tested

TutorialsNinja Demo E-Commerce Website

## Project Features

- Launch the web browser
- Login to the application
- Search for a product
- Add a product to the cart
- Update product quantity
- Verify cart details
- Capture screenshots
- Generate HTML execution report
- Execute automated test cases using PyTest

## Project Structure

```text
Folder 2 - Capstone Project/
├── Source Code/
│   ├── README.md
│   └── test_ecommerce.py
│
├── Project Report/
│   ├── README.md
│   └── Capstone_1_Selenium_Project_Report (M4).pdf
│
├── Reports/
│   ├── README.md
│   ├── report.html
│   └── assets/
│       └── style.css
│
├── Screenshots/
│   ├── README.md
│   ├── 01_product_search.png
│   ├── 02_product_added.png
│   └── 03_cart_verified.png
│
├── Demonstration Video/
│   └── README.md
│
└── README.md
````

## How to Run

1. Install Python.
2. Install the required Selenium and PyTest packages.
3. Open the project folder in the terminal.
4. Run the test file using:

```bash
python -m pytest test_ecommerce.py -v
```

5. To generate the HTML execution report, use:

```bash
python -m pytest -v --html=reports/report.html --self-contained-html
```

## Test Execution

The automated test cases cover the main e-commerce workflow:

1. Login validation
2. Product search
3. Adding the product to the cart
4. Updating the cart quantity
5. Verifying cart details

The execution outputs are documented through the screenshots and HTML execution report available in the `Screenshots` and `Reports` folders.

## Project Report

The complete Capstone Project report is available in the `Project Report` folder.

## Demonstration Videos

The project demonstration videos have already been uploaded to Google Drive.

The GitHub repository contains a README inside the `Demonstration Video` folder with the Google Drive link.

The Google Drive folder contains:

1. Project Demonstration
2. Execution Part

## Repository Contents

This Capstone Project folder contains the source code, project report, execution outputs, screenshots, README documentation, and demonstration video link required for the project submission.
