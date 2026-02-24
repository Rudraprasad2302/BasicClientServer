# 🌐 Basic Client-Server Application (Java)

A simple multi-threaded Client-Server application built using **Java Sockets**.  
This project demonstrates how network communication works between a client and a server using TCP.

---

## 📌 Project Overview

The Basic Client-Server application simulates real-time communication between multiple clients and a server.

It helps in understanding:

- Socket Programming
- TCP Communication
- Multi-threading
- Input/Output Streams
- Client handling logic

---

## ✨ Features

- 🌍 TCP-based communication
- 👥 Multiple client support (if multi-threaded)
- 💬 Message exchange between client and server
- 🖥 Console-based interaction
- 🔄 Continuous communication until exit

---

## 🛠 Tech Stack

- **Language:** Java
- **Concepts Used:**
  - Socket Programming
  - TCP Protocol
  - Multi-threading
  - InputStream & OutputStream
  - Exception Handling

---

## 📂 Project Structure

```
BasicClientServer/
│
├── Server.java
├── Client.java
└── README.md
```

*(File names may slightly vary depending on your implementation)*

---

## ⚙️ How It Works

1️⃣ Server starts and listens on a specific port.  
2️⃣ Client connects to the server using IP address and port number.  
3️⃣ Server accepts the connection request.  
4️⃣ Client and Server exchange messages using input/output streams.  
5️⃣ Communication continues until one side exits.

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```
git clone https://github.com/Rudraprasad2302/BasicClientServer.git
cd BasicClientServer
```

### 2️⃣ Compile Java Files

```
javac *.java
```

### 3️⃣ Start the Server

```
java Server
```

### 4️⃣ In Another Terminal, Start the Client

```
java Client
```

---

## 🧠 Concepts Practiced

- Creating ServerSocket and Socket
- Accepting client connections
- Reading and writing data using streams
- Handling multiple clients (if implemented)
- Thread management
- Exception handling in networking

---

## 🚀 Future Enhancements

- GUI-based client (JavaFX / Swing)
- Secure communication (SSL)
- Chat room implementation
- File transfer functionality
- Logging system

---

## 🎯 Learning Outcomes

Through this project, I improved:

- Understanding of networking fundamentals
- Real-time communication logic
- Java multi-threading concepts
- Debugging socket errors

---

## 👤 Author

**Rudra Prasad**  
📧 rudraprasad2302@gmail.com  
🔗 GitHub: https://github.com/Rudraprasad2302  

---

⭐ If you like this project, consider giving it a star!
