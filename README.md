# 💬 Java Socket Chat Application

A simple multi-client chat application built using Java Socket Programming. This project demonstrates core networking concepts including client-server architecture, multithreading, and real-time message broadcasting.

---

## 🚀 Features

* 🔗 Multi-client support
* 💬 Real-time messaging
* 🧵 Multi-threaded server handling
* 📡 Client-server architecture
* 🖥️ Console-based interface
console 
---

## 🛠️ Technologies Used

* Java
* Socket Programming
* Multithreading
* I/O Streams

---

## 📂 Project Structure

```
Java-Socket-Chat-App/
│── ChatServer.java
│── ChatClient.java
│── README.md
```

---

## ▶️ How to Run

### 1️⃣ Compile the files

```bash
javac ChatServer.java
javac ChatClient.java
```

### 2️⃣ Start the Server

```bash
java ChatServer
```

### 3️⃣ Start Clients (in multiple terminals)

```bash
java ChatClient
```

---

## ⚙️ How It Works

* The server listens on a specific port for incoming client connections.
* Each client is handled in a separate thread.
* Messages sent by one client are broadcast to all other connected clients.
* The system uses TCP sockets for reliable communication.

---

## 📌 Learning Outcomes

* Understanding of TCP/IP networking
* Hands-on experience with Java Sockets
* Implementation of multi-threading
* Real-time data communication

---

## 🚧 Future Enhancements

* GUI using Java Swing or JavaFX
* Private messaging
* User authentication system
* Message timestamps

---

## 👨‍💻 Author

**Vikas S Mirji**
Computer Science Engineering Student | Java & DSA Enthusiast

---

⭐ If you found this project helpful, give it a star!
