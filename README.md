# 🌤️ Weather App – Real-Time Weather Forecast Application

A modern and responsive web application that provides real-time weather information based on user location or searched cities. Built to deliver accurate weather forecasts with a clean and intuitive user interface.

🔗 Live Website: https://weather-app-react-omega-rosy.vercel.app


---

## 📖 Project Overview

The Weather App fetches real-time weather data from the OpenWeatherMap API and displays it in a user-friendly dashboard.  
It allows users to search any city, view current weather conditions, temperature, humidity, wind speed, and weather description with relevant icons.  

The project is designed with performance, responsiveness, and visual clarity in mind, making it suitable for desktop and mobile users.

---

## 🎯 Project Objectives

- Develop a real-time weather information application
- Integrate OpenWeatherMap API for accurate data
- Provide responsive and visually appealing UI
- Implement search functionality for cities worldwide
- Showcase skills in API integration, React, and frontend design

---

## 🧠 Technology Stack

### Frontend
- React.js
- Vite
- JavaScript (ES6+)
- Tailwind CSS
- Axios (for API requests)
- Framer Motion (animations)

### API
- OpenWeatherMap API

### Deployment
- Vercel

---

## ✨ Key Features

- Real-time weather data fetching  
- Search functionality for cities globally  
- Display of temperature, humidity, wind speed, and weather conditions  
- Responsive design for mobile and desktop  
- Smooth UI animations and transitions  
- Clean and modern interface with weather icons  

---

## 📂 Project Structure

Weather-App/
│
├── public/
│   └── assets/        # Static images and icons
│
├── src/
│   ├── components/    # React components
│   ├── pages/         # Main page views
│   ├── utils/         # Helper functions (API calls etc.)
│   ├── App.jsx
│   └── main.jsx
│
├── .gitignore
├── index.html
├── package.json
└── README.md

---

## ⚙️ Environment Variables Setup

Create a `.env` file in the root directory and add your OpenWeatherMap API key:

VITE_WEATHER_API_KEY=your_openweathermap_api_key

Add the same value in **Vercel → Project Settings → Environment Variables** during deployment.

---

## 🚀 Installation & Local Setup

git clone https://github.com/indreshharshan/Weather-app.git  
cd Weather-app  
npm install  
npm run dev  

---

## 🔄 Application Workflow

1. User opens the Weather App in a browser  
2. App fetches weather data from OpenWeatherMap API  
3. User searches for a city or allows geolocation  
4. Real-time weather details are displayed instantly  
5. Data includes temperature, humidity, wind speed, and condition  

---

## 🔐 Security & Best Practices

- API key secured using environment variables  
- No sensitive information exposed on GitHub  
- Responsive design for cross-device compatibility  
- Clean and maintainable React codebase  

---

## 🌐 Deployment

The application is deployed using **Vercel**:

Steps:  
1. Push code to GitHub  
2. Import the repository into Vercel  
3. Configure environment variable (API key)  
4. Deploy the app  

---

## 👨‍💻 Author

Indresh Harshan  
📧 Email: indreshharshan26@gmail.com  

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🌟 Conclusion

This Weather App demonstrates skills in React, API integration, responsive design, and frontend development.  
It delivers real-time weather information with a modern interface, suitable for users seeking quick and accurate weather updates.
