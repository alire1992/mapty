# 🗺️ Mapty - Map Your Workouts

**Mapty** is an interactive fitness application that allows users to log their running and cycling workouts directly on a map. Using the browser's Geolocation API, the app tracks the user's current location and pins workouts to an interactive map powered by Leaflet.js.

> **Note:** This project was built to solidify my understanding of Object-Oriented Programming (OOP) in Vanilla JavaScript, the Geolocation API, and external library integration.

## ✨ Features

- 📍 **Geolocation:** Automatically detects the user's current location on startup to center the map.
- 🗺️ **Interactive Map:** Click anywhere on the map to add a new workout at that specific coordinate.
- 🏃‍♂️ **Running & Cycling:** Log specific workouts with tailored metrics (Pace & Cadence for running; Speed & Elevation for cycling).
- 💾 **Persistent Data:** Uses the browser's `localStorage` to save workouts, so data persists even after refreshing the page.
- 🎨 **Dynamic UI:** The form dynamically changes based on the selected workout type (hiding/showing specific inputs).


## 🛠️ Technologies Used

- **Core:** Vanilla JavaScript (ES6+)
- **Architecture:** Object-Oriented Programming (Classes, Inheritance, Private Fields)
- **Mapping:** [Leaflet.js](https://leafletjs.com/) (OpenStreetMap)
- **Browser APIs:** Geolocation API, LocalStorage API
- **Styling:** Custom CSS3 (Flexbox/Grid)

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mapty.git
