🧭 About This Project

This project is a simple React Geolocation App that demonstrates how to access and display a user’s current GPS coordinates using the browser’s Geolocation API.
It allows users to get their latitude and longitude, view it directly on OpenStreetMap, and tracks how many times they have requested their position.

The project also showcases the use of:

Custom React Hooks (useGeolocation)

State management with useState

Asynchronous geolocation requests

Error handling and loading states

📘 README
📍 Features

Fetches user’s real-time location using navigator.geolocation.

Displays latitude and longitude with a clickable map link.

Handles loading and error states gracefully.

Counts how many times the user has requested their position.

Uses a custom hook (useGeolocation) for cleaner and reusable logic.

⚙️ How It Works

Click the “Get my position” button.

The browser asks for permission to access your location.

Once allowed, your coordinates (latitude & longitude) appear on screen.

You can click the link to open your position on OpenStreetMap.

Each click increments a counter showing how many times you’ve requested your location.

🧩 Technologies Used

React (useState, custom hooks)

JavaScript

Browser Geolocation API

OpenStreetMap

🚀 How to Run

Clone this repository:

git clone https://github.com/your-username/geolocation-app.git


Navigate to the project folder:

cd geolocation-app


Install dependencies:

npm install


Run the app:

npm start


Open your browser at:

http://localhost:3000

💡 Example Use Case

This project is great for learning:

How to build custom hooks in React.

How to interact with browser APIs.

How to manage loading, error, and success states in a UI.
