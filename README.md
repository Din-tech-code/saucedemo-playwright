# SauceDemo Playwright Tests

Automated UI tests for https://www.saucedemo.com, written in Python with Pytest and Playwright.

## Setup

1. Install Python 3.12.
2. Create a virtual environment: `py -3.12 -m venv venv`
3. Activate it (Windows Command Prompt): `venv\Scripts\activate`
4. Install the packages: `pip install pytest-playwright`
5. Install the browsers: `playwright install`

## Run the tests

1. Run all tests: `pytest`
2. Run with the browser visible: `pytest --headed`