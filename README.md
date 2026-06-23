# 🌦️ Weather App

A modern and responsive Weather Application built using React.js that allows users to check real-time weather information for any city around the world. The application fetches live weather data from a weather API and displays important weather details in a clean and user-friendly interface.

## 🚀 Features

- Search weather by city name
- Real-time weather information
- Displays current temperature
- Shows humidity levels
- Displays wind speed
- Weather condition and description
- Dynamic weather icons
- Loading spinner while fetching data
- Error handling for invalid city names
- Responsive design for mobile and desktop devices

## 🛠️ Tech Stack

- React.js
- JavaScript (ES6+)
- CSS3
- HTML5
- OpenWeather API
- Fetch API / Axios



Example:

### Home Page
![Home Page](screenshots/home.png)

### Weather Result
![Weather Result](screenshots/weather.png)

## 📂 Project Structure

src/
├── components/
│   ├── Weather.js
│   ├── Spinner.js
├── App.js
├── App.css
├── index.js
└── assets/

## ⚙️ Installation

1. Clone the repository

```bash
git clone https://github.com/harsh-tech74/Weather-app.git
```

2. Navigate to the project directory

```bash
cd Weather-app
```

3. Install dependencies

```bash
npm install
```

4. Start the development server

```bash
npm start
```

5. Open your browser and visit

```text
http://localhost:3000
```

## 🔑 API Configuration

1. Get a free API key from OpenWeather.
2. Create a `.env` file in the project root directory.
3. Add your API key:

```env
REACT_APP_WEATHER_API_KEY=your_api_key_here
```

4. Restart the development server.

## 🌍 How It Works

1. Enter a city name in the search box.
2. Click the search button.
3. The application sends a request to the weather API.
4. Weather data is fetched and displayed instantly.
5. If an invalid city is entered, an error message is shown.

## ✨ Future Enhancements

- 5-Day Weather Forecast
- Hourly Forecast
- Geolocation Support
- Dark Mode
- Light/Dark Theme Toggle
- Recent Search History
- Weather Maps Integration
- Multiple Language Support
- Air Quality Index (AQI)
- Sunrise and Sunset Information

## 🎯 Learning Outcomes

This project helped in learning:

- React Components
- React State Management
- API Integration
- Asynchronous JavaScript
- Conditional Rendering
- Responsive UI Design
- Error Handling
- Component Reusability

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to the branch

```bash
git push origin feature-name
```

5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License.

## 👨‍💻 Author

Harsh Raj

GitHub: https://github.com/harsh-tech74

---

⭐ If you found this project useful, please consider giving it a star on GitHub.
