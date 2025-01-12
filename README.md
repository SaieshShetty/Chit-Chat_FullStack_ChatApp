# MERN Chat Application with Socket.IO
 This project is a real-time chat application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) and Socket.IO for real-time communication. The application provides a seamless and dynamic messaging experience with features like one-on-one chat, group chat, and instant notifications.
#**Table of Contents**
1.Features
2.Tech Stack
3.Demo
4.Installation
5.Usage
6.Environment Variables
7.Folder Structure
8.Future Enhancements
9.Contributing
10.License
**#Features**
1.Real-time messaging with Socket.IO.
2.User authentication and authorization using JWT.
3.Persistent chat history with MongoDB.
4.Typing indicators and read receipts.
5.Responsive UI for mobile and desktop.
6.Online/offline user status updates.
7.Group and private chat functionality.
**#Tech Stack**
Frontend: React.js, Material-UI (or your preferred styling library, I have used Tailwind CSS)
Backend: Node.js, Express.js
Database: MongoDB with Mongoose
Real-Time Communication: Socket.IO
Authentication: JWT and bcrypt
**#ScreenShots**
![Login Page](https://github.com/user-attachments/assets/d51b1cb3-a96d-4537-aa92-17d2720ff724)
![Home Page](https://github.com/user-attachments/assets/ef73ccf4-fce8-47c7-be34-1e65ece88e73)
![Profile Page](https://github.com/user-attachments/assets/1e96bcf2-01af-4672-bc3f-501e2a5c4d46)
![Settings Page](https://github.com/user-attachments/assets/d2715032-94b0-46b6-9d79-5d3bb6df6b9f)
**#Installation**
```bash
# Step 1: Clone the Repository
git clone https://github.com/SaieshShetty/Chit-Chat__FullStack-ChatApp.git
cd Chit-Chat__FullStack-ChatApp

# Step 2: Install Dependencies

# Backend Dependencies
npm install

# Frontend Dependencies
cd Frontend
npm install
cd ..

# Step 3: Set Up Environment Variables
# Create a .env file in the root directory and add the following variables:
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
SOCKET_PORT=your_socket_port

# Step 4: Run the Application

# Start the Backend Server
npm run server

# Start the React Frontend
npm run client

# Run Both Servers Concurrently
npm run dev
```
**#Environment Variables**
Ensure the following environment variables are configured in your .env file:

MONGO_URI: MongoDB connection string.
JWT_SECRET: Secret key for signing JWT tokens.
SOCKET_PORT: Port for the WebSocket server.   

**#Folder Structure**
project-root/
├── Frontend/           # React frontend
│   ├── src/
│   ├── public/
│   └── package.json
├── Backend/           # Backend
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── index.js
├── .env              # Environment variables
├── package.json
└── README.md

#**Future Enhancements**
Add multimedia sharing (images, videos, files).
Implement push notifications for mobile devices.
Add end-to-end encryption for enhanced security.
