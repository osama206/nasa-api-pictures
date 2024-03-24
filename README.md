# NASA APOD Web Application

This repository contains a web application that allows users to browse images from NASA's Astronomy Picture of the Day (APOD) API and save their favorite images.

## Description

The NASA APOD web application fetches images from NASA's APOD API and allows users to save their favorite images. Users can view additional details about the images and remove saved favorites.

## Features

- Fetch images from NASA's APOD API
- Save favorite images
- Remove saved favorites
- View additional details about images

## Getting Started

To get started with the NASA APOD web application, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/osama206/nasa-api-pictures.git
   ```

2. Change directory to the cloned repository:
   ```
   cd nasa-api-pictures
   ```

## Usage

To use the web application, open the `index.html` file in a web browser. You can browse through the images, save your favorite ones, and view additional details.

## Demo

You can access the live demo of the NASA APOD web application hosted on GitHub Pages [here](https://osama206.github.io/nasa-api-pictures).

## Files Included

- `index.html`: HTML file containing the structure of the web page.
- `style.css`: CSS file containing styles for the web page.
- `script.js`: JavaScript file containing functionality for the web application.

## Credits

This project utilizes the following resources and documentation:

- **[Loaf Animated SVG Generator](https://getloaf.io/)**: This tool is used to generate animated SVG images for loader animations in the web application. It enhances user experience by providing engaging visual feedback during data loading processes.

- **[NASA APOD API Demo](https://api.nasa.gov/planetary/apod?api_key=DEMO_KEY)**: The API endpoint provided by NASA allows the application to fetch images and related data. By integrating this API, the web application can display a curated selection of astronomy images.

- **[NASA API Documentation](https://api.nasa.gov/)**: The official documentation provided by NASA outlines the usage of their APIs, including endpoints, parameters, and response formats. It helps developers understand how to interact with NASA's services effectively.

- **[W3Schools - includes](https://www.w3schools.com/jsref/jsref_includes.asp)**: This resource provides documentation and examples for JavaScript's `includes` method. It is used within the project to check if a particular URL is included in the list of saved favorites.

- **[W3Schools - JSON.stringify](https://www.w3schools.com/js/js_json_stringify.asp)**: The documentation on JSON.stringify from W3Schools is referenced to understand how to convert JavaScript objects into JSON strings. This method is used to store favorite images in the browser's `localStorage`.

- **[Mozilla - Object.values](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_objects/Object/values)**: Mozilla's documentation on Object.values is used to understand how to extract the values of an object as an array. This functionality is utilized in the project to iterate through the list of favorite images.

- **[W3Schools - JSON.parse](https://www.w3schools.com/js/js_json_parse.asp)**: The documentation provided by W3Schools on JSON.parse is used to understand how to parse JSON strings back into JavaScript objects. It is employed in the project to retrieve saved favorites from the browser's `localStorage`.

- **[Mozilla - Delete Operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/delete)**: Mozilla's documentation on the Delete Operator is referenced to understand how to delete properties from an object. This operator is used in the project to remove saved favorites from the list.

- **[Mozilla - scrollTo](https://developer.mozilla.org/en-US/docs/Web/API/Window/scrollTo)**: The scrollTo method documentation from Mozilla is used to understand how to scroll the window to a specific position. It is utilized in the project to scroll the page to the top when switching between different sections.
