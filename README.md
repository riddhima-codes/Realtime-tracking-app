# Realtime Tracking App

A simple real-time device tracking application that shows the live location of users on a map.

## Features
- Real-time location tracking
- Live map updates
- Multiple users can connect simultaneously
- Markers appear/disappear when users connect or disconnect

## Tech Stack
- Node.js
- Express.js
- Socket.IO
- Leaflet.js
- Geolocation API
- EJS

## How it Works
1. The browser gets the user's location using the Geolocation API.
2. The location is sent to the server using Socket.IO.
3. The server broadcasts the location to all connected clients.
4. The map updates the marker positions in real time.

## Installation

Clone the repository:

bash
git clone https://github.com/riddhima-codes/Realtime-tracking-app.git
cd Realtime-tracking-app


Install dependencies:

bash
npm install


Start the server:

bash
node app.js


Open the browser:


http://localhost:3000


## Project Structure


Realtime-tracking-app
│
├── public
│   ├── css
│   └── js
│
├── views
│   └── index.ejs
│
├── app.js
├── package.json
├── package-lock.json
└── README.md



## Author
Riddhima Agrawal
