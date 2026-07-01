# Live Tracking System 📍

A real-time location tracking web application that uses the browser's Geolocation API and Leaflet.js to display a user's current location on an interactive map. The application continuously tracks and updates the user's position, making it suitable for navigation, delivery tracking, and location-based services.

## Features

* 📍 **Real-Time Location Tracking**: Continuously tracks the user's current location.
* 🗺️ **Interactive Map**: Displays location using OpenStreetMap and Leaflet.js.
* 🔄 **Automatic Location Updates**: Updates the user's position in real time.
* 🎯 **Location Accuracy Circle**: Shows the GPS accuracy range around the user.
* 🌐 **Browser Geolocation Support**: Uses the HTML5 Geolocation API.
* 📱 **Responsive Design**: Works on desktop and mobile devices.

## Tech Stack

* **Frontend**: HTML5, CSS3, JavaScript
* **Map Library**: Leaflet.js
* **Map Provider**: OpenStreetMap
* **API**: HTML5 Geolocation API

## Project Structure

```text
Live-Tracking/
├── index.html          # Main application file
├── README.md           # Project documentation
```

## Installation & Setup

### Prerequisites

* Modern web browser (Chrome, Edge, Firefox)
* Visual Studio Code
* Live Server Extension (Recommended)

### Steps

1. Clone the repository:

```bash
git clone https://github.com/your-username/Live-Tracking.git
```

2. Open the project:

```bash
cd Live-Tracking
code .
```

3. Run the project using Live Server:

* Right-click `index.html`
* Select **Open with Live Server**

The application will run on:

```text
http://127.0.0.1:5500/index.html
```

## How It Works

1. The browser requests permission to access the user's location.
2. The Geolocation API retrieves the latitude and longitude.
3. Leaflet.js displays the location on the map.
4. A marker and accuracy circle are added.
5. The location updates automatically whenever the user moves.

## Technologies Used

* HTML5 Geolocation API
* Leaflet.js
* OpenStreetMap
* JavaScript
* CSS3

## Future Enhancements

* Route Navigation
* Multiple User Tracking
* Location History
* Distance Calculation
* Live Vehicle Tracking
* User Authentication
* Backend Integration with Node.js and MongoDB
* Real-Time Tracking using WebSockets

## Applications

* Delivery Tracking Systems
* Vehicle Tracking
* Employee Monitoring
* Emergency Services
* Navigation Applications
* Location-Based Services
