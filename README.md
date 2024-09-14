# Real-Time Tracker

This project is a **Real-Time Tracker** built using **Node.js** for the backend and **Leaflet with OpenStreetMap** for mapping and real-time tracking of locations.

## Features

- **Real-time location tracking** using Leaflet and OpenStreetMap.
- **Backend** built with Node.js.
- **Interactive Map** with markers to show current location and live updates.
- **Socket.io/WebSockets** (if applicable) for real-time data updates across multiple clients.

## Demo

![Demo Screenshot](path/to/screenshot.png)  


## Getting Started

Follow these instructions to set up the project locally.

### Prerequisites

You need to have the following installed on your machine:

- **Node.js** (v12 or higher)
- **npm** (Node package manager)
- **Git** (optional, for version control)

### Installation

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/Harsh1708V/Realtime-Device-Tracker.git
    ```

2. Navigate to the project directory:
    ```bash
    cd repository-name
    ```

3. Install the necessary dependencies:
    ```bash
    npm install
    ```

4. Start the application:
    ```bash
    npx nodemon app.js
    ```
   The app should now be running on `http://localhost:3000`.

## Technologies Used

- **Node.js**: Backend server.
- **Leaflet**: JavaScript library for interactive maps.
- **OpenStreetMap**: Free, editable map of the world.
- **Express.js**: Web framework for Node.js.
- **Socket.io** (optional): For real-time communication.

## Project Structure

```bash
|-- public/             # Static files (HTML, CSS, JS)
|-- src/                # Source files
    |-- index.js        # Entry point for the Node.js app
    |-- routes/         # API routes
    |-- models/         # Database models (if applicable)
|-- package.json        # Dependencies and project info
|-- README.md           # Project documentation
