# python-login-tests

A small Selenium WebDriver practice script that automates a login form.

## What it does

`main.py` opens the QA practice login page (`https://www.qa-practice.com/accounts/login/`) in Chrome, waits for the username and password fields, and types placeholder values into them.

## Requirements

- Python 3
- Selenium (`pip install selenium`)
- Google Chrome and a matching ChromeDriver, or Selenium's built-in driver management

## Usage

```bash
python main.py
```

Replace the `your_username` and `your_password` placeholders in `main.py` with credentials for the practice site. Do not commit real credentials.

## Status

Learning exercise. The script fills in the form fields only and contains no assertions.
