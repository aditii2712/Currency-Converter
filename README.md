# Currency-Converter
This repository contains a JavaScript-based currency converter application. The application allows users to convert amounts between different currencies using the latest exchange rates fetched from an external API. The main features include:

Dynamic Currency Conversion: Users can select currencies from dropdown menus and input an amount to convert. The application fetches the latest exchange rates and displays the conversion result.

Country Flag Updates: The application dynamically updates country flags based on the selected currencies, providing a visual representation of the chosen currencies.

Default Currency Selection: On load, the application initializes with default currency selections (USD to INR) for a quick start.

Event Handling: The application includes event listeners for button clicks and dropdown changes, ensuring a responsive user experience.

Input Validation: The code handles input validation by setting a default value of 1 if the input is empty or less than 1.

The app.js file contains the core logic for fetching exchange rates, updating the conversion result, and handling user interactions. The countryList object in codes.js maps currency codes to their corresponding country codes, which is used for updating the country flags. This application is ideal for users who need a simple and efficient way to convert currencies with real-time exchange rates.
