# Multithreaded Java TCP Server

## Overview
This is a **multithreaded TCP server** implemented in Java. It demonstrates **concurrent client handling** using a **thread pool**, allowing multiple clients to connect simultaneously. Each client receives a personalized message from the server.

This project showcases **backend concepts** such as:

- TCP networking with `ServerSocket` and `Socket`
- Multithreading and **ExecutorService**
- Robust exception handling
- Resource management with **try-with-resources**
- Scalability through thread pools

---

## Features

- Handles multiple clients concurrently
- Sends personalized messages to each client
- Thread pool ensures efficient resource usage
- Easy to run and test locally
- Ready for extension to interactive demos with WebSockets

---

## Technology Stack

- Java 17
- ExecutorService (Thread Pool)
- TCP Sockets
- Optional: Node.js + WebSocket (for interactive demos)
- Docker (for containerized deployment)

---

## Project Structure

MultithreadedServer/
│
├─ Server.java # Main Java server
├─ Client.java # Java client for testing




---

## Getting Started

### Prerequisites
- Java JDK 17+
- Docker (optional, for containerized deployment)

### Running Locally

#### 1. Compile and Run Java Server
```bash
javac Server.java
java Server


2. Run Multiple Clients
javac Client.java
java Client
