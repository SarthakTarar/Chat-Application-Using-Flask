This is a chatroom web application built with Flask and Flask-SocketIO. It allows users to create chat rooms, join existing rooms, send and receive messages in real-time, and edit room settings.

Features:
User Authentication: Users can sign up, log in, and log out securely.
Create Rooms: Authenticated users can create chat rooms and add members to them.
Real-time Messaging: Utilizes WebSocket technology for real-time communication between users in the same room.
Edit Room Settings: Room administrators can edit room name and member list.
View Chat History: Users can view older messages in a room by scrolling up.
Responsive Design: Responsive layout ensures optimal viewing experience across various devices.

Technologies Used:
Python: Backend logic and server-side scripting.
Flask: Micro web framework for Python.
Flask-SocketIO: WebSocket support for Flask.
MongoDB: NoSQL database for storing user data, room data, and chat messages.
HTML/CSS: Frontend markup and styling.
JavaScript: Client-side scripting for WebSocket communication and DOM manipulation.

Usage:
Install dependencies: pip install -r requirements.txt
Open app.py and set your secret key in the app.secret_key variable.
Connect your MongoDB database cluster by providing the connection URL in view_room.html file.

Configuration:
Secret Key: You must provide your own secret key in the app.py file to ensure the security of user sessions.
MongoDB: Connect your own MongoDB database cluster by replacing the connection URL in the view_room.html file with your cluster's URL.

Future Enhancements:
Add user profile management.
Implement message deletion functionality.
Improve UI/UX with additional styling and animations.
Feel free to contribute to this project by submitting pull requests or reporting issues!
