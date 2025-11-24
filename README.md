# vityarthi-python-project
Currency Converter
A simple and interactive command-line currency converter that converts between US Dollars (USD) and Indian Rupees (INR).
Features
* Bidirectional Conversion: Convert from USD to INR and vice versa
* Customizable Exchange Rate: Set your own exchange rate or use the default
* Input Validation: Handles invalid inputs gracefully with user-friendly error messages
* Persistent Rate: Exchange rate persists during the session until changed
* Formatted Output: Displays amounts with proper formatting and decimal places
Default Exchange Rate
The default exchange rate is set to:
1 USD = 89.62 INR
Installation
No additional installation required! This is a standalone Python script that uses only built-in functions.
Usage
1. Run the script:
bash
python currency_converter.py
2. Follow the menu prompts:
o Option 1: Convert USD to INR
o Option 2: Convert INR to USD
o Option 3: Set a new exchange rate
o Option 4: Exit the program
3. Enter the amount you want to convert when prompted
Functions
usd_to_inr(amount_usd, rate)
Converts US Dollars to Indian Rupees using the specified exchange rate.
inr_to_usd(amount_inr, rate)
Converts Indian Rupees to US Dollars using the specified exchange rate.
get_valid_amount()
Prompts user for a positive numerical amount with input validation.
get_valid_rate(default_rate)
Prompts user for a new exchange rate or uses default if no input provided.
currency_converter_tool()
Main function that runs the interactive currency converter application.
Example Usage
text
--- Simple USD/INR Converter ---
--- Setup Exchange Rate ---
   Enter the new exchange rate (1 USD = ? INR) or press Enter to keep default (89.62): 92.50

 Conversion rate set: 1 USD = 92.50 INR

--- Current Rate: 1 USD = 92.50 INR ---
What conversion do you need?
1. USD to INR (Dollar to Rupee)
2. INR to USD (Rupee to Dollar)
3. Set New Exchange Rate
4. Exit
Enter your choice (1, 2, 3, or 4): 1
   Enter the amount you want to convert: 100
100.00 USD is equal to 9,250.00 INR.
Requirements
* Python 3.x
Notes
* The exchange rate is stored as a global variable and persists throughout the session
* All amounts are formatted with thousand separators and two decimal places
* The program handles negative amounts and non-numeric inputs with appropriate error messages

