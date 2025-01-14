# Spring Chat Project

## Description
This is a real-time chat application built using Spring Boot and WebSockets. It leverages Lombok to minimize boilerplate code and uses native HTML, CSS, and JavaScript for the front-end.

## Features
- Real-time messaging
- User-friendly interface with native HTML, CSS, and JavaScript
- Efficient back-end using Spring Boot and WebSockets
- Reduced boilerplate code with Lombok

## Prerequisites
- JDK 11 or higher
- Maven
- Node.js and npm (for front-end dependencies)

## Installation

### Backend
1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd spring-chat
    ```
2. Build the project using Maven:
    ```sh
    mvn clean install
    ```
3. Run the application:
    ```sh
    mvn spring-boot:run
    ```

### Frontend
1. Navigate to the `frontend` directory:
    ```sh
    cd frontend
    ```
2. Install dependencies (if applicable):
    ```sh
    npm install
    ```
3. Build and run the front-end code:
    ```sh
    npm start
    ```

## Usage
1. Open your browser and navigate to `http://localhost:8080`.
2. Enter a username and start chatting!

## Project Structure
```plain
spring-chat/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/yourcompany/chat/
│   │   └── resources/
│   │       └── application.properties
│   └── test/
├── frontend/
│   ├── index.html
│   ├── styles.css
│   └── app.js
├── pom.xml
└── README.md
```

## Dependencies
1. Spring Boot
2. Spring WebSocket
3. Lombok
