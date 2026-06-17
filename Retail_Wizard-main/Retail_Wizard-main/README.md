# Retail Wizard: A Comprehensive Retail Shop Point Of Sale Management System

## Description
Retail Wizard is a retail shop management system designed for small businesses. It provides features such as product catalogue management, shopping cart functionality, transaction processing, and detailed reporting to streamline business operations.

## Prerequisites
1. Python 3.6 or higher installed on your system.
2. Required Python libraries:
    - pandas
    - openpyxl
    - qrcode
    - Pillow
    - fpdf
    - matplotlib
    - bcrypt
    - pyautogui
3. SQLite database file (`grocery.db`) should be present in the project directory.

## Installation
1. Download the project files to your local machine.
2. Ensure all required Python libraries are installed. Use the following command:
    ```bash
    pip install pandas openpyxl qrcode Pillow fpdf matplotlib bcrypt pyautogui
    ```

## How to Run the Application
1. Navigate to the project directory in your terminal.
2. Run the `SignUp.py` application file.
3. The sign up window of the Retail Wizard application will open; register to the product.
4. Login through your credentials.
5. Main window will appear. Click the Product Catalogue button, load the Excel file `Updated_Product_Catalogue`, select desired products and tap *Send to Main Window*.
6. Add customer's name and phone number in the top-left corner of the main window, then tap *Checkout & Pay*.
7. Tap the *Pay* button to select a payment method (cash or UPI).
8. Payment can be cancelled at any point.

## How to Access Reports
1. Click the *Reports* button in the main window.
2. Select the desired report (e.g., Transaction Report, Stock Report).
3. The selected report will open in a new window.

---

## Features
1. **Product Catalogue:** Manage product details such as category, brand, price, and stock availability. Load data from Excel.
2. **Shopping Cart:** Add/delete products and calculate total price.
3. **Transaction Processing:** Record customer and transaction data. Export invoice to JSON.
4. **Reports:** Access reports including:
    - Profit & Loss Report
    - Stock Report
    - Sales Report
    - Transaction Report
5. **Checkout and Payment:** Complete transactions and proceed with payment.

---
