# Suementum - Momentum Clone

A beautiful Momentum clone with modern glass-morphism design. Features include clock, weather, to-do list, and daily quotes.

## Features

- **Clock**: Real-time clock with clean design
- **Greeting**: Personalized greeting with user's name
- **Weather**: Current weather and location display
- **To-Do List**: Task management with smooth animations
- **Quotes**: Daily motivational quotes
- **Background**: Random background images
- **Modern UI**: Glass morphism effects with blur and transparency
- **Responsive**: Optimized for all screen sizes

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript (Vanilla)
- **Design**: Glass morphism, CSS animations
- **API**: OpenWeatherMap API
- **Storage**: Local Storage for user data persistence
- **Optional Backend**: Node.js, Express (for API key protection)

## How to Start

### Client-side Only (Simple)

1. Clone this repository
2. Get your OpenWeatherMap API key from [here](https://openweathermap.org/api)
3. Open `index.html` in your browser

### Server-side Option (For API Key Protection)

If you want to hide your API key using a proxy server (Please check server branch):

1. Clone this repository
2. Install packages:
   ```bash
   npm install express dotenv
   ```
3. Create `.env` file in the root directory:
   ```
   WEATHER_API_KEY=your_api_key_here
   ```
4. Start the server:
   ```bash
   node server.js
   ```
5. Open `http://localhost:3000` in your browser

## Project Structure

    suementum/
    ├── css/
    │   └── style.css          # Modern UI styles with glass morphism
    ├── js/
    │   ├── background.js      # Background image handler
    │   ├── clock.js          # Real-time clock
    │   ├── greetings.js      # User greeting logic
    │   ├── quotes.js         # Quotes generator
    │   ├── todo.js           # To-do list manager
    │   └── weather.js        # Weather API integration
    ├── img/                  # Background images
    │   ├── 0.jpeg
    │   ├── 1.jpeg
    │   └── 2.jpeg
    └── index.html           # Main HTML structure

## Security Notes

- Client-side: API key is exposed but simpler to set up
- Server-side: API key is protected but requires server setup
- User data is stored locally using localStorage
- Choose the setup based on your security needs
