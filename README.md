# Local Explorer

Local Explorer is a full-stack application that helps users discover local activities based on their location, real-time weather, and personalized activity suggestions.

The app uses geolocation, Weatherstack API for weather data, and Google Maps for visualizing the user's location and nearby points of interest. It features a modern UI built with React, Bootstrap, and Framer Motion.

---

## Features

- Get user location using browser geolocation
- Fetch real-time weather data using Weatherstack API
- Suggest activities based on weather conditions
- Search weather and suggestions by city
- Display location using Google Maps
- Responsive UI with Bootstrap
- Smooth animations using Framer Motion

---

## Technologies Used

### Backend

- Python
- Flask
- Flask-CORS
- Requests
- python-dotenv
- Weatherstack API

### Frontend

- React
- Axios
- Bootstrap
- Framer Motion
- Google Maps JavaScript API
- `@react-google-maps/api`

---

## Project Structure

```text
local-explorer/
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   └── .env
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── .env
├── README.md
└── .gitignore
```

---

## Prerequisites

Before running this project, make sure you have:

- Node.js and npm installed
- Python 3 installed
- API key for Weatherstack
- API key for Google Maps

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/local-explorer.git
cd local-explorer
```

---

## Backend Setup

Navigate to the backend folder:

```bash
cd backend
```

Create a virtual environment:

```bash
python -m venv env
```

Activate the virtual environment:

### macOS / Linux

```bash
source env/bin/activate
```

### Windows

```bash
env\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Create a `.env` file:

```bash
touch .env
```

Add your API key:

```env
WEATHERSTACK_API_KEY=your_weatherstack_api_key
```

Run the Flask server:

```bash
python app.py
```

---

## Frontend Setup

Open a new terminal and navigate to the frontend folder:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file:

```bash
touch .env
```

Add your Google Maps API key:

```env
REACT_APP_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
```

Start the React app:

```bash
npm start
```

---

## Usage

### Geolocation

Click the **Get My Location** button to allow the app to detect your current location.

### City Search

Use the search box to fetch weather data and activity suggestions for a specific city.

### Map

View your location and nearby points of interest on an interactive Google Map.

---

## Environment Variables

### Backend `.env`

```env
WEATHERSTACK_API_KEY=your_weatherstack_api_key
```

### Frontend `.env`

```env
REACT_APP_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
```

---

## Deployment

For production deployment, you can use:

### Backend

- Render
- Heroku
- AWS
- Railway

### Frontend

- Vercel
- Netlify
- GitHub Pages

Make sure to configure environment variables on your hosting platform.

---

## Future Improvements

- Improve activity recommendation logic
- Add database support
- Save favorite locations
- Add user authentication
- Add nearby restaurants, parks, and events
- Improve mobile experience

---

## Author

Developed as a full-stack web application project.

---

## License

This project is licensed under the MIT License.
