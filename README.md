# 💬 Multithreaded Chat Application (Java)

## 📌 Internship Task - 3

**Title:** Multithreaded Chat Application
**Objective:** Build a client-server chat application using Java sockets and multithreading to handle multiple users in real time.

---

## 🧾 Project Description

The **Multithreaded Chat Application** is a Java-based client-server system that enables multiple users to communicate with each other in real time.

The server manages multiple client connections simultaneously using multithreading, while each client can send and receive messages instantly. This project demonstrates core networking concepts and concurrent programming in Java.

---

## 🎯 Features

* 💬 Real-time messaging between multiple clients
* 🌐 Client-server architecture using sockets
* 🔄 Multithreading to handle multiple users simultaneously
* 📡 Broadcast messages to all connected clients
* ❌ Graceful handling of client disconnections
* 🧵 Dedicated thread for each client

---

## 🛠️ Technologies Used

* **Java**
* **Socket Programming (`java.net.Socket`, `ServerSocket`)**
* **Multithreading (`Thread`, `Runnable`)**
* **Input/Output Streams**

---

## ⚙️ How It Works

### 1. Server

* Starts on a specific port
* Listens for incoming client connections
* Creates a new thread for each connected client
* Broadcasts messages to all clients

### 2. Client

* Connects to the server using IP and port
* Sends messages to the server
* Receives messages from other clients in real time

---

## ▶️ How to Run

### Step 1: Compile the files

```bash id="q8h6js"
javac Server.java
javac Client.java
```

### Step 2: Start the Server

```bash id="tq4zcl"
java Server
```

### Step 3: Start Clients (in multiple terminals)

```bash id="9h9x0x"
java Client
```

---

## 📂 Project Structure

```id="p3j5mn"
/Multithreaded-Chat-App
 ├── Server.java
 ├── Client.java
 └── README.md
```

---

## 📸 Sample Output

### Server:

```id="3s0gq7"
Server started...
Client connected: User1
Client connected: User2
```

### Client:

```id="5v8w2m"
User1: Hello!
User2: Hi there!
```

---

## ⚠️ Error Handling

The application handles:

* Client disconnection
* Network interruptions
* Input/output exceptions

---

## 📚 Learning Outcomes

* Understanding client-server architecture
* Implementing socket programming in Java
* Using multithreading for concurrent users
* Managing real-time communication systems

---

## 📌 Conclusion

This project successfully demonstrates how to build a real-time chat system using Java sockets and multithreading. It provides practical experience in networking and concurrent programming.

---

## 🚀 Future Enhancements

* GUI-based chat interface (JavaFX/Swing)
* Private messaging between users
* User authentication system
* Message history storage

---

## 👨‍💻 Author

Keerthi HS
Internship Project Submission
