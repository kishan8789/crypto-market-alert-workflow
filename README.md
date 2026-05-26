# Crypto Market Daily Alert Workflow

## Project Overview

This project is an automated crypto market alert workflow built using n8n.

The workflow automatically fetches cryptocurrency market data from the CoinGecko API, processes the data, checks price change conditions, and sends alerts to Telegram.

---

## Features

* Automatic scheduled execution
* Fetches top 5 cryptocurrency market data
* Processes and formats API response
* Checks if price change is greater than 5%
* Sends Telegram notifications
* Includes basic error handling

---

## Technologies Used

* n8n
* CoinGecko API
* Telegram Bot API
* JavaScript

---

## Workflow Steps

1. Schedule Trigger starts the workflow automatically
2. HTTP Request fetches crypto market data
3. Code node processes and formats the data
4. IF node checks price change conditions
5. Telegram node sends alerts to the user

---

## API Used

CoinGecko Market API:

https://api.coingecko.com/api/v3/coins/markets?vs_currency=usd&order=market_cap_desc&per_page=5&page=1

---

## Output

The workflow sends crypto alerts directly to Telegram with:

* Coin Name
* Symbol
* Current Price
* 24 Hour Price Change

---

## Author

Kishan Kumar

