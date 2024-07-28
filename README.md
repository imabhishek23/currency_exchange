# Currency Converter Web Application

This is a simple currency converter web application that allows users to convert an amount from one currency to another. The application uses JavaScript and an external API to fetch the latest exchange rates.

## Features

- Convert amounts between different currencies
- Automatically fetches the latest exchange rates
- Displays country flags based on the selected currency

## Technologies Used

- HTML
- CSS
- JavaScript
- [Currency API](https://github.com/fawazahmed0/currency-api)

## Project Structure

- `index.html`: The main HTML file that contains the structure of the web page.
- `style.css`: The CSS file that contains styles for the web page.
- `app.js`: The JavaScript file that contains the main logic for fetching exchange rates and updating the UI.
- `codes.js`: The JavaScript file that contains the list of country codes and their corresponding flags.

## Setup and Installation

1. **Clone the repository:**
    ```bash
    git clone <repository-url>
    ```

2. **Navigate to the project directory:**
    ```bash
    cd currency-converter
    ```

3. **Open `index.html` in your preferred web browser:**
    ```bash
    open index.html
    ```

## How to Use

1. **Enter the amount:**
   - Enter the amount you wish to convert in the input field.

2. **Select currencies:**
   - Choose the source currency from the "From" dropdown.
   - Choose the target currency from the "To" dropdown.

3. **Get exchange rate:**
   - Click the "Get Exchange Rate" button to fetch and display the conversion rate.
