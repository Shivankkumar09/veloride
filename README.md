# Veloride - Cab Booking App

Veloride is a cab booking application that provides a seamless experience for both riders and captains (drivers). The platform offers live tracking, multiple vehicle choices, and real-time navigation powered by Google Maps API.

## Features

- **Separate Login/Signup for Riders and Captains**
- **Live Tracking** of rides using Google Maps API
- **Multiple Vehicle Choices** (Bike, Car, Auto, etc.)
- **Real-Time Navigation** for Captains
- **User-Friendly Interface** for a smooth booking experience

## Tech Stack

- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **Maps & Tracking:** Google Maps API

## Installation & Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/veloride.git
   cd veloride
   ```

2. Install dependencies for the client and server:
   ```sh
   cd client
   npm install
   cd ../server
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the server folder and add:
     ```env
     MONGO_URI=your_mongodb_uri
     JWT_SECRET=your_secret_key
     GOOGLE_MAPS_API_KEY=your_google_maps_api_key
     ```

4. Start the development servers:
   ```sh
   # Start backend server
   cd server
   npm start
   ```
   ```sh
   # Start frontend server
   cd client
   npm start
   ```

## Usage

- **Riders:** Sign up, select a vehicle type, enter the destination, and book a ride.
- **Captains:** Log in, accept ride requests, and navigate to the rider's location using live tracking.

## Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request with improvements or bug fixes.


## Team Members

- **Shivank Kumar**
- **Ankan Kar**
- **Sumit Baghel**

