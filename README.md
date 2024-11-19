# Weather App

A simple weather application that allows users to get the current weather information for a city by entering its name. The app fetches real-time weather data from the OpenWeatherMap API.

## Features

- Fetches current weather information for a city.
- Displays:
  - City name.
  - Temperature in Fahrenheit.
  - Humidity percentage.
  - Weather description.
  - Weather emoji based on the condition.
- Displays an error message if:
  - The city name is invalid.
  - The API request fails.

## Project Structure

### Files

1. **index.html**  
   Contains the structure of the webpage and includes the form for user input, a section to display weather data, and linked styles and scripts.

2. **style.css**  
   Provides styling for the application, including layout, button styles, and card design for weather information display.

3. **index.js**  
   Implements functionality for fetching weather data from the OpenWeatherMap API, processing the data, and dynamically updating the UI.

---

## Installation and Setup

### Prerequisites

- A text editor (e.g., Visual Studio Code).
- A browser to view the app.
- Internet connection to fetch data from the OpenWeatherMap API.

### Steps

1. Clone or download the repository to your local machine.
2. Replace the `apiKey` in `index.js` with your own API key from [OpenWeatherMap](https://openweathermap.org/).
3. Open the `index.html` file in your browser to run the app.

---

## How It Works

1. **User Input:**  
   - Enter a city name in the input field and click the "Get Weather" button.

2. **API Fetch:**  
   - Sends a request to the OpenWeatherMap API with the provided city name and the API key.

3. **Data Processing:**  
   - Extracts and formats the weather data (temperature, humidity, description).

4. **UI Update:**  
   - Displays the weather information inside the styled card.

5. **Error Handling:**  
   - Shows a meaningful error message if the API call fails or no city is entered.

---

## Technologies Used

- **HTML:** Structure of the application.
- **CSS:** Styling for a user-friendly interface.
- **JavaScript:** Fetching API data, processing it, and updating the DOM.

---

## Preview

### Input Form
- A text box for entering the city name.
- A button to submit the request.

### Weather Card
- Displays the weather details dynamically.
- Includes styled text and emoji for a better user experience.

---

## Example Output

**For a valid city:**
`City: New York`
`Temperature: 75.3°F` 
`Humidity: 60%` 
`Description: Clear Sky` 
`Weather Emoji: 🌞`


**For an invalid city:**
`Error: Could not fetch weather data`


---

## Acknowledgments

- **OpenWeatherMap API:** For providing free access to weather data.
- Icons and emojis inspired by weather conditions.

## License

This project is open-source and free to use for personal or educational purposes.
