# 🌤️ Weather App

A simple **Weather Web Application** built using **HTML**, **CSS**, and **JavaScript**.
This app allows users to get real-time weather information for any city in the world using the **Google API** for location input and weather data fetching.

---

## 🚀 Features

* 🌎 **Search by Location** — Enter any city name to get live weather updates.
* ☀️ **Real-Time Weather Data** — Displays temperature, humidity, wind speed, and weather conditions.
* 📍 **Google API Integration** — Fetches location details and corresponding weather information.
* 💡 **User-Friendly Interface** — Minimal, responsive, and easy-to-use design.
* 🎨 **Custom Styling** — Built with clean HTML and CSS for a visually appealing layout.

---

## 🛠️ Technologies Used

* **HTML5** — Structure of the application.
* **CSS3** — Styling and layout.
* **JavaScript (ES6)** — Logic for fetching and displaying weather data.
* **Google API** — Used for location and weather data retrieval.

---

## ⚙️ How It Works

1. The user enters a **city name** in the search box.
2. The app uses the **Google API** to fetch location coordinates (latitude and longitude).
3. It then calls the **Google Weather API** (or you can use other integrated API) to get weather data for that location.
4. The weather information — such as temperature, humidity, feel like, and weather condition — is displayed dynamically on the page.

---

## 📸 Screenshot

![App Screenshot](/weatherapp-gui.jpg)

---

## 🧩 Project Structure

```
weather-app/
│
├── app/
|   │
|   ├── index.html       # Main HTML file
|   ├── app.css          # CSS for styling the app
|   |__ app.js           # JavaScript file with app logic
├── assets/              # GUI picture
└── README.md            # Project documentation
```

---

## 🔑 Setup & Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Munazza-Iman/WeatherApp.git
   ```

2. Navigate to the project folder:

   ```bash
   cd weather-app
   ```

3. Open the `index.html` file in your browser.

4. Make sure to **add your Google API key** in the JavaScript file:

   ```javascript
   const apiKey = "YOUR_GOOGLE_API_KEY";
   ```

5. Type any city name in the search bar and press **Enter** to see real-time weather updates!

---

## 💡 Future Enhancements

* 🌦️ Add 5-day weather forecast.
* 📱 Improve responsive design for mobile devices.
* 🕒 Show sunrise and sunset times.
* 🎨 Include theme options (light/dark mode).
* 🗺️ Add an interactive map showing searched location.

---

## 👨‍💻 Author

**Munazza Iman**

---