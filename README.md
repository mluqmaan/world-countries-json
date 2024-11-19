# World Countries JSON

This repository provides a comprehensive JSON file with detailed information about all countries around the world. The data includes:

- Country name
- ISO Alpha-2 and Alpha-3 codes
- ISO Numeric code
- Currency details (code, name, symbol)
- Base64-encoded flag images

The JSON file can be used for various purposes such as building country pickers, displaying flags, or creating tools and apps that require country information.

## File Overview

### `countries.json`
- Contains a list of countries with the following fields:
  - `id`: A unique identifier for the country.
  - `name`: The full name of the country.
  - `isoAlpha2`: ISO Alpha-2 code (e.g., `US` for the United States).
  - `isoAlpha3`: ISO Alpha-3 code (e.g., `USA` for the United States).
  - `isoNumeric`: ISO Numeric code.
  - `currency`: An object containing:
    - `code`: Currency code (e.g., `USD`).
    - `name`: Currency name (e.g., `Dollar`).
    - `symbol`: Currency symbol (e.g., `$`).
  - `flag`: A Base64-encoded string representing the country's flag image.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/world-countries-json.git

2. Access the countries.json file in your project.

3. Example usage in JavaScript:
   ```bash
   const countries = require('./countries.json');
   countries.forEach(country => {
    console.log(`Country: ${country.name}, Currency: ${country.currency.name}`);
    });

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute this project as long as the original copyright notice is included. See the `LICENSE` file for more details.
