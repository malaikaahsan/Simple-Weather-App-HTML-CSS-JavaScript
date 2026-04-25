# Dynamic Weather App

[![Deployed on Vercel](https://img.shields.io/badge/Deployed_on-Vercel-black?style=for-the-badge&logo=vercel)](https://simple-weather-app-html-css-java-sc.vercel.app/)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

A sleek, dynamic weather application that provides real-time weather data and multi-day forecasts. Built with a modern "Glassmorphism" UI, this project demonstrates advanced API handling, modular JavaScript architecture, and responsive web design.

**🚀 Live Demo:** [View the live app on Vercel](https://simple-weather-app-html-css-java-sc.vercel.app/)

---

## 🚀 Features

* **Real-Time Weather & Forecasts:** Displays current temperature, humidity, wind speed, "feels like" temperature, and a dynamic multi-day forecast.
* **Smart API Caching:** Implements a JavaScript `Map` to cache previously searched cities, drastically reducing redundant API calls and improving load times.
* **Optimized Search Requests:** Utilizes the `AbortController` API to cancel pending network requests if the user types a new query, preventing race conditions.
* **Glassmorphism UI:** Features a modern, semi-transparent frosted glass aesthetic using CSS backdrop filters.
* **Modular Codebase:** JavaScript logic is cleanly separated into ES6 modules (e.g., extracting date/time formatting to a `utils.js` file) for maintainability.
* **Loading States:** Includes a custom SVG loading animation while data is being fetched.

## 🛠️ Tech Stack

* **Markup:** HTML5
* **Styling:** Vanilla CSS3 (Flexbox, Glassmorphism)
* **Logic:** Vanilla JavaScript (ES6 Modules, Async/Await, Fetch API)
* **API:** [WeatherAPI.com](https://www.weatherapi.com/)
* **Deployment:** Vercel

## 📂 Project Structure

```text
.
├── index.html       # Main application structure
├── style.css        # Glassmorphism UI and responsive styling
├── script.js        # Main logic, API fetching, and DOM manipulation
└── utils.js         # Helper functions (date and time formatting)
```
💻 Getting Started (Local Development)
Because this project uses ES6 JavaScript Modules (<script type="module">), browsers will block the script from running if you just double-click the index.html file. You must run this on a local server.

Clone the repository:

```
git clone [https://github.com/malaikaahsan/Simple-Weather-App-HTML-CSS-JavaScript.git](https://github.com/malaikaahsan/Simple-Weather-App-HTML-CSS-JavaScript.git)
```
Navigate to the folder:

```
cd Simple-Weather-App-HTML-CSS-JavaScript
```
Run a Local Server:

If using VS Code, install the Live Server extension.

Right-click index.html and select "Open with Live Server".

👨‍💻 Author
Malaika Ahsan

GitHub: @malaikaahsan
