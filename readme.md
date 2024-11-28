## Chattrly - Group-Based Chat Application

Chattrly is a real-time, group-based chat application that allows users to connect, communicate, and collaborate through secure and fast messaging. Built with Flask, Flask-SocketIO, and WebSockets, Chattrly offers seamless communication with real-time message updates.


## Features

- Real-time messaging: Instant message updates between users.
- Group chats: Create and join group chats for easy collaboration.
- WebSocket support: Fast communication with WebSocket technology.
- Secure: Messages are sent and received securely.


## Technologies Used

- Flask: A lightweight Python web framework used to build the app.
- Flask-SocketIO: Enables WebSocket support for real-time messaging.
- Eventlet: Provides asynchronous networking support.
- Gunicorn: WSGI HTTP server for running Flask applications in production.
- WebSockets: Real-time two-way communication protocol.


## Installation
1. Clone the repository

First, clone the repository to your local machine.

git clone https://github.com/psroy007/chattrly.git
cd chattrly


2. Install the dependencies

Install the required Python dependencies using pip.

pip install -r requirements.txt


3. Run the application

python app.py

The app will be available at http://127.0.0.1:5000 by default.

Alternatively, you can run it with Gunicorn for production use:

gunicorn -w 4 app:app
