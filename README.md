# Aptiv Shares Outstanding Web App

This is a minimal, static, single-page web application that fetches and displays the common stock shares outstanding for Aptiv (CIK 0001521332) from the SEC's XBRL API.

## Features
- Displays the maximum and minimum shares outstanding values along with their respective fiscal years.
- Allows users to input a different CIK in the URL to fetch data for other companies.
- Responsive design using Bootstrap for better user experience.

## Usage
1. Open `index.html` in a web browser.
2. To view data for a different company, append `?CIK=XXXXXXXXXX` to the URL, replacing `XXXXXXXXXX` with the desired 10-digit CIK.

## Data Source
The data is fetched from the SEC's API endpoint: `https://data.sec.gov/api/xbrl/companyconcept/CIK{CIK}/dei/EntityCommonStockSharesOutstanding.json`

## Note
Ensure to set a descriptive User-Agent in compliance with SEC guidelines.