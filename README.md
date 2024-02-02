# Spring boot chat application
This documentation provides information on the technologies used and instructions on how to run the real-time chat application locally.

## Technologies Used

### Backend

1. **Spring Boot:**
   - Description: Spring Boot is used as the backend framework for building the chat application.
   - Website: [Spring Boot](https://spring.io/projects/spring-boot)

2. **WebSocket:**
   - Description: WebSocket is utilized for real-time bidirectional communication between the server and clients.
   - Website: [WebSocket](https://spring.io/guides/gs/messaging-stomp-websocket/)

3. **Spring Data JPA:**
   - Description: Spring Data JPA is used for data access and database interaction.
   - Website: [Spring Data JPA](https://spring.io/projects/spring-data-jpa)

4. **PostgreSQL Database:**
   - Description: PostgreSQL is used as the relational database for storing user information and chat history.
   - Website: [PostgreSQL](https://www.postgresql.org/)

### Frontend

[Include frontend technologies here if applicable.]

## How to Run Locally

Follow the steps below to run the real-time chat application locally on your machine.

### Prerequisites

1. Java Development Kit (JDK) 11 or later: [Download JDK](https://www.oracle.com/java/technologies/javase-downloads.html)
2. Apache Maven: [Download Maven](https://maven.apache.org/download.cgi) (if using Maven for build)

### Steps

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/your-chat-app.git
   cd your-chat-app
Configure Database:

Open src/main/resources/application.properties.
Configure the database connection properties (URL, username, password).
2. **Build and Run:**

Using Maven:
bash
Copy code
mvn clean install
mvn spring-boot:run
Alternatively, use your preferred IDE to run the application.
Access the Application:

3. **Open a web browser and navigate to http://localhost:8080 to access the chat application.**

4. **Demo Video:** https://www.loom.com/share/85807a8f2b024aa79c16a3109c7772a2
5. **Output Images:**
![image](https://github.com/2001akash/spring-boot-chat-application/assets/88871193/e7160435-dfcc-474f-8896-60dfb12b9998)
![image](https://github.com/2001akash/spring-boot-chat-application/assets/88871193/22e7fc47-c3c7-46be-86df-f9bf9886a068)


