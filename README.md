# Node.js HTTP Server

This project is a simple Node.js HTTP server that handles basic routing and logs incoming requests to a file. It demonstrates using the http and fs modules in Node.js to handle HTTP requests and perform file operations.

Features : 
Handles requests to the root (/) and the /about route.
Logs each incoming request with a timestamp to a file named log.txt.
Provides basic responses for defined routes and a 404 Not Found for undefined routes.

# 🚀 Getting Started

## Prerequisites
Node.js (version 12 or higher)

## Installation
1. Clone the repository:
```bash
git clone https://github.com/SohamAgawane/Node-http-Server.git
```
2. Navigate to the project directory:
```bash
cd Node-http-Server
```
3. Install dependencies:
```bash
npm install
```

## Running the Server
To start the server, run the following command in the project directory:
```bash
npm start
```
The server will start and listen on port 8000. You will see the message "Server Started" in your terminal.

## Usage
Open your browser and go to [http://localhost:8000](http://localhost:8000) to see the homepage message.

Visit [http://localhost:8000/about](http://localhost:8000/about) to see the about message.

Any other routes will return a 404 Not Found message.

## Logging
All incoming requests are logged in the log.txt file with a timestamp and the requested URL.

# Project Structure
```bash
Node-http-Server/
├── index.js          # Main server file
├── log.txt           # File where logs are saved
├── package.json
```
