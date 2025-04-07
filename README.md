# Suementum - Momentum Clone

This is a clone of Momentum Chrome extension. It has nice design and useful functions like clock, weather, and to-do list. You can see quotes and greeting message too.

## Features

- **Clock**: Shows current time with clean design
- **Greeting**: Says hello with your name
- **Weather**: Shows weather and your city
- **To-Do List**: You can write and manage your tasks
- **Quotes**: Shows random quotes for motivation
- **Background**: Changes background image randomly
- **Responsive**: Looks good on desktop and mobile

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express
- **API**: OpenWeatherMap (through proxy server)

## How to Start

1. Clone this project
2. Install packages:
   ```bash
   npm install
   ```
3. Make .env file and write your OpenWeatherMap API key:
   ```bash
   WEATHER_API_KEY=your_api_key_here
   ```
4. Run the server:
   ```bash
   npm run dev
   ```
5. Open your browser and go to `http://localhost:3000`

## Folder Structure

    momentum-clone/
    ├── css/
    │   └── style.css
    ├── js/
    │   ├── background.js
    │   ├── clock.js
    │   ├── greetings.js
    │   ├── quotes.js
    │   ├── todo.js
    │   └── weather.js
    ├── img/
    │   ├── 0.jpeg
    │   ├── 1.jpeg
    │   └── 2.jpeg
    ├── index.html
    ├── package.json
    └── server.js

## Security

- Weather API key is securely stored on the server
- User data (name and to-do list) is stored locally using localStorage
