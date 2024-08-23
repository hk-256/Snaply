

## Overview

This project is a MERN (MongoDB, Express.js, React.js, Node.js) stack social networking application where users can connect and share content. The application utilizes yarn for quick build processes and integrates Cloudinary for image storage.

## Features
- **Infinite Scrolling**: Dynamically loads additional posts as the user scrolls, enhancing user experience.
- **MongoDB with Connect-Mongo Session**: Utilizes MongoDB as the database with connect-mongo-session for handling user sessions.
- **Real-Time Chat**: Powered by socket.io and socket.io-client for real-time peer-to-peer messaging.
- **Video Calls**: Implements peer-to-peer video calling using socket.io and PeerJS (WebRTC).
- **Global State Management**: Employs React Redux for efficient state management across the application.

## Installation Guide

To run this app on your local machine, follow these steps:

1. Clone the repository: Use the command git clone https://github.com/hk-256/Snaply.git to clone the repository.


2. Navigate to the project directory: Change your directory to the client folder to run the client-side code.


3. Install the dependencies for the server and client: Execute `npm i` in both the client and server directories to install all required dependencies.


4. Set up environment variables:

- Create a `.env` file in the `server` directory.
- Include all necessary environment variables, such as database connection information, Cloudinary credentials, and SMTP email settings.

5. Start the server: start server and client by `npm start`
6. Start the client : start server and client by `yarn start`

7. Open your browser and visit `http://localhost:3000` to see the app in action.

## Contributing

Contributions are highly encouraged! If you have suggestions or improvements, feel free to open a pull request. For substantial changes, please start by opening an issue to discuss your ideas.

## You can contact me for any tips/query anytime .
