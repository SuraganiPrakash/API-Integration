# API-INTIGRATION

*COMPANY* : CODETECH IT SOLUTION

*NAME* : SURAGANI PRAKASH

*INTERN ID* : CT06DL1242

*DOMAIN* : FULL STACK WEB DEVELOPMENT

*DURATION* : 6 WEEKS

*MENTOR NAME* : NEELA SANTOSH

## API-INTIGRATION

### Building a Weather App Using OpenWeatherMap API

Creating a dynamic and responsive weather web application involves integrating HTML, CSS, and JavaScript with a third-party service like the OpenWeatherMap API. This guide explains the steps required to build such an application and outlines key features and concepts essential for understanding how the app works.

### Step 1: Obtain an API Key from OpenWeatherMap

Before starting development, you need to sign up on [OpenWeatherMap](https://openweathermap.org/api). Once registered and logged in, you can generate a free API key. This key is a unique code that allows your app to authenticate and make requests to the OpenWeatherMap API. It is required to access the weather data for any location.

### Step 2: Create the Webpage

The webpage is built using three core technologies:

HTML (HyperText Markup Language): Used to structure the content of the webpage. This includes elements such as headings, input fields, and buttons that form the user interface (UI).

CSS (Cascading Style Sheets): Used to style the webpage and make it responsive. It ensures the layout adapts to different screen sizes such as desktops, tablets, and smartphones, improving accessibility and visual appeal.

JavaScript:** Handles the dynamic functionality of the app. It allows the webpage to fetch weather data from OpenWeatherMap and display it in real time without refreshing the page.

# Key Features of the App

### ✅ Responsive Layout

The layout is designed to be fully responsive. It adjusts according to the device’s screen size. On smaller devices like smartphones, the input field and button are compact and optimized for mobile interaction.

### ✅Dynamic Content Loading

Instead of reloading the page every time new weather data is needed, JavaScript's `fetch()` API is used to retrieve data asynchronously. This ensures a smoother and faster user experience.

### ✅ Error Handling

The application includes error handling to manage invalid input or failed API requests. If the user enters an incorrect city name or if the API is unavailable, an appropriate error message is displayed. This provides immediate feedback and improves the overall user experience.

### How the App Works

### User Interface (UI)

The app features a clean and straightforward interface. At the top, there’s a search bar where users can input the name of a city. Upon clicking the “Get Weather” button, weather data is displayed below the search field without needing to reload the page.

### API Integration with OpenWeatherMap

The JavaScript function `getWeather()` is triggered when the user clicks the button. This function uses the `fetch()` method to request weather information from OpenWeatherMap, based on the city name entered. The API key is included in the request URL. Replace `'YOUR_API_KEY'` in the code with the actual API key obtained from your OpenWeatherMap account.

---

### Important Terms and Concepts

API Key: A secure code used to authenticate your app with OpenWeatherMap. It ensures your app is authorized to access the requested data.

OpenWeatherMap: A widely used service that provides current weather data, forecasts, and historical weather records through an easy-to-use API.

HTML: The foundation of all webpages, used to define the structure of your app, such as where buttons, forms, and text appear.

CSS: Controls the styling of the webpage, including colors, fonts, spacing, and layout. It ensures the design is visually appealing and mobile-friendly.

JavaScript: Adds interactivity to the webpage. In this app, it fetches weather data and updates the content dynamically.

Fetch API: A built-in JavaScript method for making HTTP requests to external services like OpenWeatherMap. It enables real-time data retrieval without reloading the page.

Responsive Layout: A web design approach that allows the page to adapt to various screen sizes for better user experience across devices.

Dynamic Content Loading: Refers to the ability to load and update content without a full page refresh, providing a seamless experience.

Error Handling: A programming practice that helps manage unexpected user input or issues like network failures. It improves the reliability and usability of the application.

User Interface (UI): The visual part of the app that users interact with. In this case, the search bar and weather display area form the core UI components.

By combining these technologies and features, you can build an interactive and user-friendly weather application that fetches and displays real-time data efficiently across all devices.

# API INTIGRATION OUTPUT :

![Image](https://github.com/user-attachments/assets/bf00f279-ba29-4686-8f55-25eadcf81951)

