# Smart Irrigation System

## Problem Statement

Traditional irrigation methods often result in water wastage because irrigation is performed manually without considering the actual soil moisture or environmental conditions. Farmers may overwater or underwater crops, reducing crop health and wasting water.

## Proposed Solution

The Smart Irrigation System automates irrigation by continuously monitoring soil moisture, temperature, and humidity. The system uses an ESP32 microcontroller to collect sensor data and control the water pump automatically based on predefined soil moisture thresholds. A web dashboard displays real-time sensor readings and weather information, allowing users to monitor the system remotely.

## Features

* Automatic irrigation based on soil moisture level
* Real-time monitoring of temperature and humidity
* Weather information display
* User-friendly web dashboard
* Responsive interface for desktop and mobile devices
* Real-time sensor data visualization

## Hardware Components

* ESP32 Development Board
* Soil Moisture Sensor
* DHT22 Temperature and Humidity Sensor
* Relay Module
* Water Pump
* LCD Display
* Jumper Wires
* Power Supply

## Software Components

* React.js
* Vite
* JavaScript
* Tailwind CSS
* HTML
* CSS
* Node.js
* Git & GitHub

## Technologies Used

### Frontend

* React.js
* Vite
* Tailwind CSS

### IoT

* ESP32
* Sensor Interfacing
* GPIO Programming

### Development Tools

* Visual Studio Code
* Git
* GitHub

## System Workflow

1. Soil moisture sensor measures the moisture level.
2. DHT22 measures temperature and humidity.
3. ESP32 processes the sensor data.
4. If soil moisture is below the threshold, the relay turns ON the water pump.
5. Once sufficient moisture is reached, the relay turns OFF the pump.
6. Sensor data is displayed on the web dashboard and LCD.

## Project Structure

```text
smart-irrigation/
├── public/
├── src/
│   ├── Components/
│   ├── pages/
│   ├── api/
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── package.json
├── vite.config.js
└── README.md
```

## Output

The Smart Irrigation System successfully:

* Monitors soil moisture in real time.
* Displays temperature and humidity readings.
* Controls the water pump automatically based on soil moisture.
* Provides a responsive dashboard for monitoring sensor data.
* Reduces unnecessary water consumption through automated irrigation.

## Future Enhancements

* AI-based plant disease detection
* Weather forecast-based irrigation scheduling
* Mobile application
* Firebase cloud integration
* Notification alerts
* Water usage analytics

## Author

**Jeeva**

Electrical and Electronics Engineering (EEE)

GitHub: https://github.com/J-Jeeva-18
