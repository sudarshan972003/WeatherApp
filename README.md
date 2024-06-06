# WeatherApp

A weather application built using Vite and React that provides real-time weather updates. This app fetches data from the Visual Crossing Weather API and displays the current weather conditions, temperature, wind speed, humidity, and more. The background and icons change dynamically based on the weather conditions.

## Features

- Displays current weather conditions with dynamic background and icons.
- Provides detailed information including temperature, wind speed, humidity, and heat index.
- Allows users to search for weather information by location.
- Responsive and visually appealing UI built with Tailwind CSS.

## Installation

Follow these steps to run the project locally:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/sudarshan972003/WeatherApp.git
   cd WeatherApp

2. **Create React App:**
   ```bash
   npm create vite@latest

   Project name: ./
   Package name: WeatherApp
   Select a framework: React
   Select a variant: JavaScript

3. **Install dependencies:**

   ```bash
   npm install

4. **Set up Tailwind CSS:**

   ```bash
   npm install -D tailwindcss postcss autoprefixer
   npx tailwindcss init -p

5. **Run the app:**

   ```bash
   npm run dev

The app should now be running on http://localhost:5173/.


## Required Installations

Make sure to have the following tools installed on your system:

1. **Node.js and npm:**
   To check if Node.js and npm are installed, run:
   ```bash
   node -v
   npm -v

2. **Vite:**
   Vite is used for fast frontend tooling. Install it globally using npm:
   ```bash
   npm install -g vite

3. **Tailwind CSS:**
   A utility-first CSS framework for rapid UI development.
   ```bash
   npm install -D tailwindcss postcss autoprefixer
   npx tailwindcss init -p

4. **Axios:**
   A promise-based HTTP client for the browser and Node.js.
   ```bash
   npm install axios

5. **React and React DOM:**
   The core libraries for building the user interface.
   ```bash
   npm install react react-dom

6. **Classnames:**
   A utility for conditionally joining classNames together.
   ```bash
   npm install classnames


## Usage
- Open the application.
- By default, the weather information for Washington, DC, USA will be displayed.
- Use the search feature to get weather updates for your desired location.

## Component Details
1. **BackgroundLayout.jsx**
   Dynamically sets the background image based on the current weather conditions.

2. **MiniCard.jsx**
   Displays a small card with the time, temperature, and weather icon.
   
3. **WeatherCard.jsx**
   Shows detailed weather information including temperature, wind speed, humidity, and conditions.

4. **Context/index.jsx**
   Manages the global state and fetches weather data from the API.

5. **Utils/useDate.jsx**
   Custom hook to get the current date and time.

6. **App.jsx**
   Main application component that integrates the search functionality, background layout, weather card, and mini cards.


## API Integration
- This app uses the Visual Crossing Weather API to fetch weather data. Ensure you have an API key from RapidAPI.
- Replace the placeholder X-RapidAPI-Key in Context/index.jsx with your API key.

  ```bash
  headers: {
    'X-RapidAPI-Key': 'your-api-key-here',
    'X-RapidAPI-Host': 'visual-crossing-weather.p.rapidapi.com'
  }

## Contributing
- Contributions are welcome! Please feel free to submit a Pull Request.

## License
- This project is licensed under the MIT License.

## Author
- Developed by Sudarshan Thiruppathi.



   







   
