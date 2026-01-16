# 🗨️ TalkHub – Real-Time Chat Application

TalkHub is a real-time web chat application built using **Spring Boot** and **WebSockets**, enabling multiple users to communicate instantly through a simple and colorful UI. The project is fully **Dockerized** for easy deployment.

---

## 🚀 Features

* Real-time messaging using WebSockets (STOMP + SockJS)
* Multi-user chat support
* Join notifications
* Clean and responsive UI
* Docker container support

---

## 🛠️ Tech Stack

* Java (JDK 21+)
* Spring Boot
* Spring WebSocket
* HTML, CSS, JavaScript
* Maven
* Docker

---

## ▶️ Run Without Docker

```bash
mvn spring-boot:run
```

Open: `http://localhost:8080`

---

## 🐳 Run With Docker

```bash
docker build -t talkhub .
docker run -p 8080:8080 talkhub
```

Open: `http://localhost:8080`

---

## 📸 Expected Output

* Chat UI loads
* Users join using username
* Messages appear in real time
* Works across multiple browser tabs

---

## 👨‍💻 Author

**Balaji Shreyan .k **
