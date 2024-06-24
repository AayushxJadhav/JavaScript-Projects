# HTML CSS JavaScript-Projects
# Weather App

This is a simple Weather App developed using HTML, CSS, and JavaScript. The application allows users to search for weather information of a specific city and displays the current temperature, humidity, wind speed, and weather conditions.

## Features

- Search for weather information by city name
- Display current temperature, humidity, wind speed, and weather conditions
- Show appropriate weather icon based on the weather condition
- Handle errors for invalid city names

## Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeatherMap API

## Prerequisites

- Web browser (Chrome, Firefox, Safari, etc.)
- Internet connection

## Setup and Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/weather-app.git
    cd weather-app
    ```

2. **Open the project in your favorite code editor:**

    ```bash
    code .
    ```

3. **Open the `index.html` file in a web browser:**

    Simply open the `index.html` file in your web browser to use the app.

## Usage

1. **Enter City Name:**
   - In the input box, type the name of the city you want to get weather information for.

2. **Search:**
   - Click the search button or press Enter to fetch the weather information.

3. **View Weather Details:**
   - The app will display the current temperature, city name, humidity, and wind speed.
   - The appropriate weather icon will be displayed based on the current weather conditions.
   - If the city name is invalid, an error message will be shown.

## Folder Structure

```
weather-app/
├── images/
│   ├── clear.png
│   ├── clouds.png
│   ├── drizzle.png
│   ├── humidity.png
│   ├── mist.png
│   ├── rain.png
│   ├── search.png
│   └── wind.png
├── style.css
└── index.html
```

## Code Explanation

### HTML (index.html)

- The HTML file contains the structure of the Weather App, including input fields, buttons, and containers for displaying weather information.
- It includes links to the CSS file (`style.css`) for styling and the JavaScript code embedded within `<script>` tags.

### CSS (style.css)

- The CSS file contains styles for the Weather App, ensuring a user-friendly and responsive design.

### JavaScript (Embedded in HTML)

- The JavaScript code handles the interaction with the OpenWeatherMap API.
- It fetches weather data based on user input and updates the DOM to display the information.
- It also handles error scenarios, such as invalid city names.

