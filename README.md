# weather-Web-app
 


This project is a web-based application that allows users to:
- Toggle between **dark mode** and **light mode**.
- Select and save custom **theme colors**.
- Fetch and display **real-time weather** data using the OpenWeather API.

---

## Features

### 1. Dark Mode
- Toggle between light and dark modes with a simple button click.
- **User preferences** are saved in `localStorage` to maintain the selected mode across sessions.

### 2. Theme Colors
- Choose from a palette of colors to customize the theme.
- Changes apply instantly to the web app interface.
- Selected theme is saved in `localStorage` for persistent user experience.

### 3. Weather Integration
- Fetch weather data for any location using the **OpenWeather API**.
- Displays the current temperature, weather condition, and more.
- Automatically detects user location if permissions are granted.

---

## How to Run the Project

1. **Clone the repository to your local machine**:
   ```bash
   git clone https://github.com/yourusername/theme-darkmode-weather.git

2. **Navigate to the project folder**:
    ```bash
    cd WEATHER-WEB-APP

3. **Replace the OpenWeather API Key**:

    - Open the script.js file in a text editor.
    - Locate the following line in javascript:

     ```bash
    const apiKey = "your_openweather_api_key_here";
    ```
    - Replace "your_openweather_api_key_here" with your actual API key from the OpenWeather API.

4. **Run the web application**:

    - Open the index.html file in your browser, or
    - Use a local server (e.g., Live Server in VS Code).
