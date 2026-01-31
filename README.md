# Playwright Automation Assessment - SwiftTranslator

This repository contains the automated test scripts for the SwiftTranslator assignment.
I've implemented 42 test cases using Playwright to check conversion accuracy and UI functionality.

## Setup Instructions

1.  **Install dependencies**
    Open the terminal in this folder and run:
    ```bash
    npm install
    npx playwright install
    ```

2.  **Run the Tests**
    To execute all test scenarios:
    ```bash
    npx playwright test
    ```

    To watch them run in the browser (headed mode with UI):
    ```bash
    npx playwright test --ui
    ```

3.  **Check Results**
    You can view the HTML test report by running:
    ```bash
    npx playwright show-report
    ```

## Project Structure

*   `tests/IT23278844_swifttranslator.spec.ts`: Main test file with all 24 positive, 10 negative, and 1 UI scenario.
*   `IT23278844_TestCases.csv`: Contains the data used for the Excel sheet export.
*   `playwright.config.ts`: Configuration settings for the test runner.

