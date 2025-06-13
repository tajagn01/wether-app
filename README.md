# Weather App 🌤️

A modern, responsive weather application built with HTML, CSS, and JavaScript that allows users to check weather conditions for any city around the world.

## ✨ Features

- 🌤️ Real-time weather data using OpenWeatherMap API
- 🌓 Dark/Light mode toggle with system preference detection
- 🎨 Dynamic background images based on weather conditions
- 📱 Fully responsive design for all devices
- 🔍 City search functionality with autocomplete
- 💾 Theme preference persistence using localStorage
- 📊 Detailed weather information including humidity, wind speed, and more
- 🌍 Support for multiple languages and units (metric/imperial)

## 🛠️ Technologies Used

- HTML5
- CSS3 (with modern features like backdrop-filter and CSS Grid)
- Vanilla JavaScript (ES6+)
- OpenWeatherMap API
- Local Storage for data persistence
- Responsive Design Principles

## 🚀 Setup and Installation

1. Clone the repository:
```bash
git clone https://github.com/tajagn01/wether-app.git
cd weather-app
```

2. Get an API key from [OpenWeatherMap](https://openweathermap.org/api)
   - Sign up for a free account
   - Navigate to your API keys section
   - Copy your API key

3. Replace the API key in `script.js`:
```javascript
const API_KEY = 'your-api-key-here';
```

4. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

## 📱 Usage

1. Enter a city name in the search box
2. Press Enter or click the Search button
3. View the current weather information
4. Toggle between dark and light mode using the theme button
5. Switch between Celsius and Fahrenheit using the unit toggle

## 📊 Weather Information Displayed

- City name and country
- Current temperature
- Weather description
- Feels like temperature
- Humidity percentage
- Wind speed and direction
- Sunrise and sunset times
- Weather icon

## 🖼️ Background Images

The app automatically changes its background based on the current weather condition:
- Clear/Sunny: Bright, sunny landscapes
- Cloudy: Overcast cityscapes
- Rainy: Rainy urban scenes
- Thunderstorm: Dramatic storm images
- Snowy: Winter wonderland scenes

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Weather data provided by [OpenWeatherMap](https://openweathermap.org/)
- Background images from [Unsplash](https://unsplash.com/)
- Icons from [Weather Icons](https://erikflowers.github.io/weather-icons/)

## 📞 Support

If you encounter any issues or have questions, please:
1. Check the [Issues](https://github.com/yourusername/weather-app/issues) section
2. Create a new issue if your problem isn't already listed
3. Contact the maintainers for urgent matters

---

Made with ❤️ by Tajagn Garala
