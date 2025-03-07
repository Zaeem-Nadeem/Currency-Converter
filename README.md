# Currency Converter

This is a simple web application that allows users to convert between different currencies. The application fetches real-time exchange rates and displays the equivalent amount in the target currency. Users can select their desired "from" and "to" currencies from dropdown lists, enter an amount, and get the converted value instantly.

## Features

- **Currency Selection**: Users can select the currencies they want to convert from and to using dropdown menus.
- **Real-Time Exchange Rates**: The app fetches real-time currency exchange rates from a public API.
- **Conversion Calculation**: After entering an amount, the app will display the converted value based on the selected currencies.
- **Country Flags**: The app displays flags corresponding to the selected currencies.
- **Responsive Design**: The layout is responsive and works well on mobile devices.

## How It Works

1. **Currency Selection**: Users select the currencies for conversion using the dropdown lists.
2. **Amount Input**: Users input the amount they wish to convert in the "Amount" input field.
3. **Exchange Rate Fetching**: The application fetches the exchange rate from the API based on the selected "from" and "to" currencies.
4. **Result Display**: The converted amount is displayed along with the corresponding currencies.

## Setup Instructions

1. **Clone the repository** or download the files.
2. Open the `index.html` file in your web browser to run the Currency Converter app.
3. Select the "From" and "To" currencies, input an amount, and press the "Convert" button to see the converted value.

## File Structure

```plaintext
├── index.html         # The main HTML file containing the structure of the currency converter
├── style.css          # The CSS file for styling the converter layout
├── script.js          # The JavaScript file containing the logic for fetching exchange rates and updating the UI
