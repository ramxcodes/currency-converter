## Currency Converter Web Application

The provided HTML code represents the structure of a "Currency Converter" web application. This application allows users to convert currency from one country to another using the current exchange rate. Below is a documentation of the various sections and elements present in the web application.

### HTML Structure:

1. **Meta Tags**: The `<meta>` tags in the `<head>` section provide information about the character encoding and viewport settings for the web application.

2. **Font Awesome**: The web application uses Font Awesome version 6.4.0 for displaying icons. It is linked using the `<link>` tag.

3. **Title and Stylesheet**: The title of the web application is set as "Currency Converter", and a custom stylesheet "style.css" is linked to provide additional styling.

4. **Container**: The `<div>` element with the class "container" serves as the main container for the entire web application.

5. **Heading**: The `<h2>` element displays the heading "Currency Converter".

6. **Form**: The `<form>` element contains the input fields and elements required for currency conversion.

7. **Amount Input**: The amount input field is represented using the `<div>` element with the class "amount". It contains a `<p>` element with the text "Amount" and an `<input>` element with an initial value of "1".

8. **Currency Conversion Box**: The `<div>` element with the class "convert-box" contains the elements for currency conversion.

   - **From Currency**: The `<div>` element with the class "from" represents the "From" currency selection. It contains a `<p>` element with the text "From" and a custom dropdown select box with a country flag image and a `<select>` element.

   - **Exchange Icon**: The `<div>` element with the class "reverse" contains the Font Awesome icon `<i>` for exchanging currencies.

   - **To Currency**: The `<div>` element with the class "to" represents the "To" currency selection. It contains a `<p>` element with the text "To" and a custom dropdown select box with a country flag image and a `<select>` element.

   - **Result**: The `<div>` element with the class "result" initially displays the text "Getting exchange rate...". After clicking the "Get Exchange Rate" button, the actual exchange rate result will be displayed here.

   - **Button**: The `<button>` element triggers the conversion process when clicked. It has the text "Get Exchange Rate".

9. **Footer**: The `<p>` element with the id "footer" displays the credit for the creator of the web application and includes a link to the creator's portfolio.

### JavaScript:

The web application includes two JavaScript files:

1. "countries.js": This script likely contains the list of countries and their currency codes, which will be used to populate the dropdown select boxes with available currencies.

2. "index.js": This script handles the currency conversion logic and interactions with the DOM elements.

### Styling:

The web application uses a custom stylesheet "style.css" to style the various elements and layout of the application.

## Usage:

To use the Currency Converter web application, follow these steps:

1. Ensure that the "countries.js" and "index.js" JavaScript files are correctly linked in the HTML file.

2. Open the "index.html" file in a web browser to view the web application.

3. Enter the amount you want to convert in the "Amount" input field.

4. Select the currency you want to convert from in the "From" dropdown select box.

5. Select the currency you want to convert to in the "To" dropdown select box.

6. Click the "Get Exchange Rate" button to display the converted amount in the "Result" section.

The web application will use the exchange rate to perform the currency conversion and display the result in the "Result" section.

Please note that the actual functionality of the currency conversion and exchange rate retrieval may require additional server-side code or API integration, which is not provided in the given HTML code.

---

This documentation provides an overview of the Currency Converter web application's structure and functionality. To access the actual web application with its full functionality and styling, refer to the provided HTML code and ensure all required files are present and linked correctly. If you have any questions or need further assistance, please feel free to contact the creator, [Ram](https://ramxcodes.github.io/portfolio/).
