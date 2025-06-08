# Test WebView Project

This project demonstrates various functionalities related to web views, including cookie management, local storage, content security policies, file access, and pop-up/modal windows. Below is a brief description of each file included in the project.

## Files Overview

- **archivo-locales.html**: 
  - Contains a button that attempts to access local files using an input element of type file. It alerts the user whether access is permitted.

- **cookies.html**: 
  - Provides functionality to set, get, and delete cookies using JavaScript. It includes buttons for each action and displays results in a designated area.

- **index.html**: 
  - Integrates all other HTML files, images, and JavaScript into a single document.

- **prueba-csp.html**: 
  - Tests Content Security Policy (CSP) settings. It includes inline scripts, external scripts, and images to check if they load correctly based on the CSP rules defined.

- **script-local.js**: 
  - A JavaScript file that runs when the DOM is fully loaded. It checks for localStorage availability and updates the content of a specific paragraph element.

- **test_dom_storage.html**: 
  - Demonstrates how to use localStorage to save and retrieve data. It includes an input field and a button to save the input value.

- **test_ventanas.html**: 
  - Tests the functionality of opening pop-up windows and modals. It includes buttons to open new tabs and a modal window.

- **webview-multiples-pestanas.html**: 
  - Provides links and buttons to open various websites in new tabs and includes functionality to open a modal window.

## Usage

To use this project, open the `index.html` file in a web browser. This will allow you to access all functionalities provided by the other HTML files through a single interface. Each feature can be tested by clicking the respective buttons or links.

## Requirements

- A modern web browser that supports JavaScript and HTML5 features.
- Ensure that local file access permissions are set appropriately in your browser settings if testing file access functionalities.

## License

This project is open-source and available for modification and distribution.