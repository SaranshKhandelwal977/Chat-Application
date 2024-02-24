# MERN Chat Application with Socket.IO

Welcome to the MERN Chat Application with Socket.IO repository! This application provides real-time chat functionality using the MERN (MongoDB, Express.js, React.js, Node.js) stack along with Socket.IO.

## Table of Contents

- [1. Introduction](#1-introduction)
- [2. Features](#2-features)
- [3. Technologies Used](#3-technologies-used)
- [4. Installation](#4-installation)
- [5. Usage](#5-usage)
- [6. Live Demo](#6-live-demo)
- [7. Contributing](#7-contributing)

## 1. Introduction

The MERN Chat Application with Socket.IO allows users to sign up or log in and chat with other users in real-time. Upon signing up, users are visible to all other users in their contact list, and they can initiate chats instantly.

## 2. Features

The key features of the MERN Chat Application with Socket.IO include:

- **User Authentication**: Users can sign up or log in securely.
- **Real-time Chat**: Users can chat with other users in real-time using Socket.IO.
- **Contact List**: All signed-up users are visible to each other in their contact list.
- **Message History**: Chat history is maintained for easy reference.

## 3. Technologies Used

The project is built using the following technologies:

- **Frontend**:
  - React.js: For building the user interface.
  - HTML and CSS: For structuring and styling the application.
- **Backend**:
  - Node.js: For server-side logic.
  - Express.js: As the web application framework.
  - MongoDB: For database management.
  - Socket.IO: For real-time communication.
- **Authentication**:
  - JWT (JSON Web Tokens): For user authentication.
- **Other Dependencies**:
  - Mongoose: For MongoDB object modeling.
  - Axios: For making HTTP requests.
  - React Router: For client-side routing.

## 4. Installation

To run the project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/SaranshKhandelwal977/Chat-Application.git
```

2. Navigate to the project directory:

```bash
cd chat-application
```

3. Install the dependencies for both the frontend and backend:

```bash
npm install
cd server
npm install
```

4. Set up your MongoDB database and update the connection string in the backend `.env` file.

5. Start the backend server:

```bash
npm start
```

6. Start the frontend development server:

```bash
cd ..
npm start
```

7. Open your browser and go to `http://localhost:3000` to access the application.

## 5. Usage

1. Sign up or log in with your credentials.
2. View your contacts in the contact list.
3. Initiate chats with other users by clicking on their names.
4. Send and receive messages in real-time.

## 6. Live Demo

Check out the live demo of the EdTech Project [here](https://chat-application-iota-ivory.vercel.app/).

## 7. Contributing

Contributions are welcome! If you find any issues or want to add new features, feel free to submit a pull request.
Contributions are welcome! If you find any issues or want to add new features, feel free to submit a pull request.
1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Add feature-name"`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

