"# ITPM Assignment 1 - Test Automation" 
# ITPM Assignment 1: Test Automation for Singlish Transliteration

**Student Name:** Ridmi Ahinsa
**Student ID:** IT23844056
**Target URL:** https://www.pixelssuite.com/chat-translator

## Project Overview
This project contains 50 negative test cases designed to evaluate the performance of a Singlish to Sinhala transliteration tool. It uses Python and Playwright to automate the testing process.

## Contents
* **test_automation.py**: The Playwright script used to run the automation.
* **Assignment 1 - Test cases.xlsx**: The Excel sheet containing the test data, actual results, and status.

## How to Run
1. Install dependencies: `pip install playwright openpyxl`
2. Install browser: `playwright install chromium`
3. Run the script: 
   `python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator"`
