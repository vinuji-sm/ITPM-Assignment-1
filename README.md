# ITPM Assignment 1 – SwiftTranslator Automation

Student ID: IT23557642  
Tool Used: Playwright  
Application Under Test: https://www.swifttranslator.com/

## Description
This project contains functional and UI test automation for the
SwiftTranslator (Singlish to Sinhala) web application.

Test cases were first designed and documented in Excel and then
automated using Playwright.

Both positive and negative scenarios are covered.

## How to Run the Tests
npm install
npx playwright test

## View Test Report
npx playwright show-report

## Browser Used
- Chromium (Desktop Chrome)

## Notes
Some negative test cases are intentionally marked as FAIL to validate
robustness against invalid or poorly formatted input.
