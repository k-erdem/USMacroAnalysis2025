# Charts for U.S. Economic Forecast for 2025

Welcome! In this repository, you can see the Datasets, APIs and the code I've used and developed to make necessary charts for my 2025 US Macroeconomic Analysis.

Follow the steps below after cloning your repository to run the Jupyter Notebook on your devices as well.

## Environment Setup Guide

This guide explains how to set up your environment variables and install project dependencies.

## Setting up .env file

1. Create a new file named `.env` in your project's root directory
2. Copy the contents below into your `.env` file, replacing the placeholder values with your actual credentials:

```
# API Keys
API_KEY=your_api_key
SECRET_KEY=your_secret_key
```

**Important**: Never commit your `.env` file to version control. Make sure it's listed in your `.gitignore` file.

## Installing Requirements

1. Install the requirements using pip:
```bash
pip install -r requirements.txt
```

## Troubleshooting

- If you encounter permission errors during installation, try using:
  ```bash
  pip install --user -r requirements.txt
  ```
- Make sure all environment variables in the .env file are properly set before running the application
- Verify that your virtual environment is activated (you should see `(venv)` in your terminal prompt)

## Additional Notes

- Keep your .env values secure and never share them publicly
