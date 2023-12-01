# DealSleuth: Amazon Best Deal Finder

## Introduction
Welcome to DealSleuth, a dynamic tool designed to help users find the best deals on Amazon for any product they're looking to purchase. By harnessing the power of advanced sorting algorithms and price data from priceapi.com, DealSleuth delivers top-notch deal suggestions right to your phone.

## Features
- **Product Search**: Allows users to search for any legal product available on Amazon.
- **Deal Sorting Algorithm**: Analyzes price data to sort and find the best available deals.
- **SMS Notifications**: Sends deal alerts with prices and product links directly to the user's phone via Twilio API.
- **Daily Deal Updates**: Runs automatically every day using PythonAnywhere to ensure the latest deals are always at your fingertips.

## How It Works
DealSleuth operates on a straightforward yet powerful process:
1. **Data Intake**: Collects product data, including pricing, from Amazon through priceapi.com.
2. **Deal Analysis**: The algorithm sorts the products by price and identifies the most attractive deals.
3. **Deal Compilation**: The top deals are compiled into a concise message format.
4. **SMS Delivery**: The compiled deal information is sent to the user's phone as an SMS text, including the price and a direct link to the product page on Amazon.

## Getting Started
To start receiving deal alerts from DealSleuth:
1. Clone the repository and navigate to the project directory.
2. Install the required dependencies.
3. Set up your priceapi.com and Twilio API credentials.
4. Run the script to begin your daily deal updates.

## Feedback
If you have any feedback or run into issues, please file an issue in this repository's issue tracker.

## License
DealSleuth is released under the MIT License. See the `LICENSE` file for more information.

Thank you for choosing DealSleuth - happy deal hunting!

