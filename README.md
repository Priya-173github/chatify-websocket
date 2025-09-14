# Chatify: Real-time Chat with WebSockets

This repository contains **Chatify**, a real-time chat application built using **Spring Boot** and **WebSockets**. It demonstrates a lightweight chat server implementation using the **STOMP** protocol over WebSockets, providing a simple yet effective platform for instant messaging.

---

## Features

* **Real-time Messaging:** Send and receive messages instantly.
* **Simple Frontend:** Includes a basic web-based interface for user interaction.
* **Embedded Tomcat Server:** Runs on an embedded server, making it easy to execute and deploy.

---

## Prerequisites

Before you get started, make sure you have the following installed:

* **Java 18** or a newer version
* **Maven 3.9+**

---

## Steps to Run the Project

1.  **Clone the Repository:**
    Open your terminal or command prompt and clone the project to your local machine using this command:

    ```bash
    git clone [https://github.com/Priya-173github/chatify-websocket.git](https://github.com/Priya-173github/chatify-websocket.git)
    ```

2.  **Navigate to the Project Directory:**
    Change your current directory to the cloned repository:

    ```bash
    cd chatify-websocket
    ```

3.  **Build and Run the Application:**
    Use Maven to build the project and start the embedded Tomcat server. This command will handle everything for you:

    ```bash
    ./mvnw spring-boot:run
    ```

4.  **Access the Application:**
    Once the application is running, open your web browser and go to `http://localhost:8080`. You should now see the chat interface and can start messaging in real-time.
