# CodeCollabs - Real-Time Code Sharing with Socket.io

CodeCollabs is a real-time collaborative code-sharing platform where users can create and join rooms to share and edit code together. Built using **Socket.io**, this app allows users to work on code with peers in isolated rooms, ensuring that each room has its own separate code environment.

## Features

- **Create Rooms**: Users can create new rooms for real-time code collaboration.
- **Join Rooms**: Users can join existing rooms using a unique room ID.
- **Real-Time Code Sync**: Code changes made by one user in a room are instantly synced with all other users in that room.
- **Private Rooms**: Only users with the room ID can join and collaborate in a specific room.

## Tech Stack

- **Backend**: Node.js
- **Real-Time Communication**: Socket.io
- **Frontend**: HTML, CSS, JavaScript
- **WebSocket**: For real-time communication and updates

## Installation

### Prerequisites

Make sure you have **Node.js** installed on your system. If not, download and install it from [here](https://nodejs.org/).

### Clone the Repository

```bash
git clone https://github.com/piyush136/codecollabs.git
cd codecollabs
