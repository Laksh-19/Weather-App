# Weather-App

A simple and intuitive weather application that allows users to retrieve real-time weather information for any city. This app utilizes the OpenWeather API to fetch data and dynamically displays weather conditions including temperature, humidity, and a descriptive weather emoji.

Features

- Real-Time Weather Data: Fetches current weather data for any city using the OpenWeather API.
- Dynamic UI: Displays city name, temperature, humidity, and weather description with an appropriate emoji.
- Error Handling: Provides feedback if the user enters an invalid city or if there’s an issue fetching data.
- Responsive Design: Clean and responsive interface for a seamless user experience.

Technologies Used:

HTML: For structuring the content of the app.
CSS: For styling the user interface and creating a visually appealing design.
JavaScript: For making asynchronous API calls and dynamically updating the UI with the fetched weather data.
OpenWeather API: Provides the weather data used by the app.

Installation:

Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/Laksh-19/weather-app.git
Navigate to the project directory:
bash
Copy code
cd weather-app
Open index.html in your preferred browser to view the app.

Usage:

Enter the name of a city in the input field.
Click on the "Get Weather" button.
The app will display the weather information, including:

1) City name
2) Temperature (in Fahrenheit)
3) Humidity percentage
4) Weather description with an appropriate emoji

If the city name is invalid or there is an issue with fetching the data, an error message will be displayed.

Code Overview:

HTML (index.html)

1) Form: A simple form where users can input the city name.
2) Card: A section where the weather data will be displayed.

CSS (styles.css)

1) Styling: Custom styles for the form, input fields, buttons, and weather display card.
2) Responsive Design: Ensures that the app looks good on all screen sizes.

JavaScript (index.js)

1) API Integration: Fetches weather data from the OpenWeather API.
2) Dynamic UI Updates: Updates the weather information in the UI based on the fetched data.
3) Error Handling: Provides user feedback in case of errors.
