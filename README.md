Regular Expressions Repository

This repository contains implementations of regular expressions to match specific patterns for email addresses, URLs, phone numbers,credit card numbers, time, HTML tags, hastags, and currency amounts.

The regular expressions are implemented in Python

This API collects data from various web sources and presents the relevant information based on user input.
A. How to run the APP:
You can execute the app from the command line, using either direct text input or a file as input.

- option 1: python extraction.py "Contact: user@example.com, URL: https://example.com, Phone: (123) 456-7890"
- option 2: python extraction.py path/to/large_text_file.txt --from-file

B. Output format:

Emails: ['user@example.com']
URLs: ['https://example.com']
Phone Numbers: ['(123) 456-7890']
Credit Cards: []
Times 24-hour: []
Times 12-hour: []
HTML Tags: []
Hashtags: []
Currency Amounts: []

C. Unit testing:
To verify the functionality of the extraction logic, unit tests have been provided. You can execute these tests with the following command:

python -m unittest test_extraction.py
