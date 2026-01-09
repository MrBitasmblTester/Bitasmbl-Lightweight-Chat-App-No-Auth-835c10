# Bitasmbl-Lightweight-Chat-App-No-Auth-835c10

## Description
Build a web application that allows users to join anonymous chatrooms and exchange messages in real-time using WebSockets. The focus is on fast communication, simple interface, and responsive updates without requiring user registration.

## Tech Stack
- Express.js
- React
- Socket.IO

## Requirements
- Express.js
- React
- Socket.IO

## Installation
bash
git clone https://github.com/MrBitasmblTester/Bitasmbl-Lightweight-Chat-App-No-Auth-835c10.git
cd Bitasmbl-Lightweight-Chat-App-No-Auth-835c10
npm install


## Usage
bash
npm start


## API Endpoints
- WebSocket endpoint: `/` via Socket.IO

## Implementation Steps
1. Initialize Express.js server and integrate Socket.IO.
2. Serve React build from Express.
3. Implement Socket.IO events for joining rooms and broadcasting messages.
4. Build React UI for selecting rooms and sending messages.
5. Connect React client to Socket.IO server and handle real-time updates.
6. Ensure responsive layout and basic error handling.