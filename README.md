# APIforBeginners — Building APIs for the next generation of developers

## Overview
APIforBeginners is a collection of API projects designed to help beginner to intermediate developers learn and practice building APIs using Python. This project aims to provide a hands-on learning experience, allowing developers to experiment with different API concepts and technologies.

## Tech Stack
* Python 3.10
* Flask
* Poetry for dependency management
* Cryptodome for encryption
* Requests and BeautifulSoup for web scraping

## Features
* Currency rate API: retrieves the current exchange rate between two currencies
* API endpoint for retrieving the rate: `/api/v1/<in_cur>-<out_cur>`
* Supports multiple currency pairs
* Returns the exchange rate in JSON format

## Screenshots
> 📸 Screenshots coming soon. Run the project locally to see it in action.

## Setup & Installation
1. Clone the repository using `git clone https://github.com/abdiomari/APIforBeginners.git`
2. Install the dependencies using `poetry install`
3. Activate the virtual environment using `venv\Scripts\activate` (on Windows) or `source venv/bin/activate` (on Linux/Mac)
4. Set the `FLASK_ENV` environment variable to `development` using `set FLASK_ENV=development` (on Windows) or `export FLASK_ENV=development` (on Linux/Mac)
5. Run the project using `python main.py`
6. Access the API endpoint by navigating to `http://localhost:5000/api/v1/usd-eur` in your web browser

Note: Make sure to replace `usd` and `eur` with the desired currency pair.