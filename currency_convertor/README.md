# 💱 Currency Converter Web App

A simple and responsive currency converter web application that allows users to convert amounts between different currencies using real-time exchange rates. The app includes dynamic flag loading, dark/light mode, and confirmation-based actions for better usability and accessibility.

## 🚀 Features

- 🌐 Converts between a wide range of global currencies
- 📡 Uses real-time exchange rates from ExchangeRate-API
- 🇺🇸 Displays country flags dynamically based on selected currencies
- ✅ Confirmation checkbox before exchange action is enabled
- 🔄 Swap functionality to reverse currency pairs
- 🌙 Toggle between light and dark modes
- 🔗 Quick access to live exchange rates on [xe.com](https://www.xe.com/currencyconverter/)

## 🧾 Project Structure

- ├── main.html # Main HTML structure
- ├── js/
- │ ├── script.js # Main logic and API integration
- │ └── country-list.js # Currency code to country code mapping
- ├── style.css # (Expected) Stylesheet for layout and theme


## 🛠️ Tech Stack

- HTML5
- CSS3 *(Assuming usage through style.css)*
- JavaScript (Vanilla)
- ExchangeRate-API (for currency rates)
- FlagsAPI (for flag images)

## ⚙️ How It Works

1. The user inputs an amount and selects source and target currencies.
2. The country flags are auto-loaded based on the selection.
3. On enabling the checkbox, the "Get Exchange Rate" button becomes active.
4. Upon clicking, the app fetches real-time exchange data and displays the converted amount.
5. Users can swap currencies or switch between light and dark mode.

## 📦 Setup Instructions

1. Clone or download the repository.
2. Ensure you have an internet connection (required for API and CDN resources).
3. Open `main.html` in any modern web browser.

## 🔐 Note

- You will need a valid API key from [https://www.exchangerate-api.com](https://www.exchangerate-api.com) to replace the existing key in `script.js` if the current one expires.

## Made using HTML, CSS and JavaScript
