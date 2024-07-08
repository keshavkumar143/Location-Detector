# Real-Time Location Tracker

This project is a real-time location tracker web application built using Node.js, Express, Socket.IO, and Leaflet. It allows multiple users to share their real-time geolocation with each other on a map interface.

## Features

- **Real-Time Updates:** Users can see the real-time location updates of other connected users on a map.
- **Geolocation API:** Utilizes the browser's Geolocation API to track and share user locations.
- **Interactive Map:** Uses Leaflet.js to display an interactive map with OpenStreetMap tiles.

## Technologies Used

- **Backend:** Node.js, Express
- **Real-Time Communication:** Socket.IO
- **Frontend:** HTML, CSS, JavaScript
- **Mapping Library:** Leaflet

 ## Deployment Link 
https://location-detector-68q1.onrender.com/

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone https://github.com/keshavkumar143/Location-Detector.git
   cd location-tracker
   ```

2. **Install dependencies:**
   ```
   npm install
   ```

3. **Start the server:**
   ```
   npm start / node app.js
   ```
   The server will start running on `http://localhost:3001`.

4. **Open the application:**
   Open your web browser and go to `http://localhost:3001` to see the application in action.

## How to Use

- Upon opening the application, users are prompted to allow geolocation tracking.
- Users' locations are displayed on the map in real-time.
- As users move, their markers update accordingly for all connected clients.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your improvements.

---

Feel free to customize the content based on specific details of your project and any additional features or setup instructions you might have. This template provides a basic structure covering the project description, features, setup instructions, usage guidelines, and information about contributing and licensing.
