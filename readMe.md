# 🪙 Currency Converter
A sleek, responsive, and real-time Currency Converter web application built with HTML, CSS, and Vanilla JavaScript. This tool allows users to instantly convert amounts between various global currencies using live exchange rate data.

[**🚀 Live Demo**](https://chandujeevan.github.io/Currency-Converter/e)
## 🚀 Features
- Real-Time Conversion: Fetches the latest exchange rates using the Fawaz Ahmed's Currency API.

- Dynamic Flag Updates: Automatically updates country flags when a currency is selected using     FlagsAPI.

- Wide Currency Support: Supports over 100+ global currencies via a comprehensive country code list.

- Input Validation: Restricts input to numbers only and defaults to 1 if the field is left empty.

## 💡 How It Works
- Initialization: When the page loads, the app.js script populates the dropdown menus using the countryList object from countryCodeList.js.

- User Input: The user enters an amount and selects the "From" and "To" currencies.

- API Request: Upon clicking the Convert button (or on initial load), the app sends a fetch request to the Currency API: https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/{currency}.json

- Display: The app calculates the final amount based on the fetched rate and updates the message on the screen.