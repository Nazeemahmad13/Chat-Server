# Chat Server Application

## Overview

This is a **message broadcasting application** where logged-in users can communicate with each other in real-time. The app is built in **Java** using **sockets** for network communication and includes a **basic graphical user interface (GUI)**. Users can log in, send messages, and receive messages broadcast to all active users in the chat room.

### Features:
- Real-time message broadcasting to all connected users.
- Basic login functionality for users.
- A simple and user-friendly graphical interface.
- Server-client architecture using sockets.

---

## Table of Contents
1. [Features](#features)
2. [Prerequisites](#prerequisites)
3. [Setup Instructions](#setup-instructions)
4. [Technologies and Libraries](#technologies-and-libraries)
5. [Screenshots](#screenshots)


---

## Features
- **Multi-user support**: Multiple users can connect and broadcast messages to each other simultaneously.
- **Real-time communication**: Messages sent by a user are instantly displayed on all connected clients.
- **Login system**: Users need to log in before joining the chat.
- **Basic GUI**: The app comes with a simple UI for sending and receiving messages.

---

## Prerequisites
To run the project, ensure you have the following installed:
- Java Development Kit (JDK) 8 or higher
- Basic knowledge of socket programming and networking
- IDE (IntelliJ IDEA, Eclipse, or NetBeans) for running and editing the code

---

## Setup Instructions

### 1. Clone the repository:
```bash
git clone https://github.com/username/chat-server-app.git
cd chat-server-app
```
### 2. Compile the Java code (Optional)

### 3.Run the JAR file

### 4. Login:
- Start multiple instances of the client to simulate multiple users
- Login using a unique username for each user
- Start broadcasting messages in real-time

## Technologies and Libraries

### Core Java Libraries:
- `java.net.Socket`: Used for client-server communication.
- `java.net.ServerSocket`: Listens for incoming client connections.
- `java.io.InputStream/OutputStream`: For sending and receiving data between server and clients.
- `javax.swing`: For building the basic graphical user interface (GUI).
- `java.util.concurrent.Executors`: For handling multiple client connections using threads.

### Java Classes Involved:
- `Socket`: Establishes a connection between the client and the server.
- `ServerSocket`: Binds to a specific port and listens for incoming connections.
- `PrintWriter`: Sends output to the client.
- `BufferedReader`: Reads input from the client.
- `JFrame`, `JTextField`, `JTextArea`: Provides the GUI components for chat windows.
- `Thread`: For handling multiple clients concurrently.

## Screenshots

1. **Login Window**  
   ![Login Window](path/to/login_window.png)  
  
2. **Chat Window**  
   ![Chat Window](path/to/chat_window.png)  
  
