## 📌 Introduction
 
In today’s interconnected world, seamless collaboration on documents among multiple users is
essential for productivity and efficiency.

The **Real-Time Collaborative Document Editor** is a cutting-edge application designed to
facilitate **simultaneous editing of shared documents by multiple users in real time**.
This project leverages modern web technologies to ensure scalability, performance, and security.

The system utilizes **NestJS** for the backend, **WebSockets** for real-time communication,
and robust **authentication & authorization mechanisms** to maintain data integrity,
user privacy, and secure access control.

---

## 🚀 Key Features

1. **Real-Time Collaboration**  
   Multiple users can edit the same document simultaneously with live updates.

2. **Document & User Management**  
   Create, manage, and control access to documents and users.

3. **WebSocket Client Identification**  
   Mapping of WebSocket connections with authenticated database users.

4. **Authentication & Authorization**  
   Secure user authentication using JWT with role-based access control.

5. **Conflict Resolution**  
   Handles concurrent edits to maintain document consistency.

6. **Data Persistence**  
   Automatic saving and retrieval of document changes from the database.

7. **DTO Management**  
   Clean and maintainable data flow using DTOs (Data Transfer Objects).

8. **Validation & Transformation**  
   Input validation and data transformation using `class-validator`
   and `class-transformer`.

---

## 🛠 Technology Stack

### 🔹 Frontend
- **ReactJS**
- **Context API** (State Management)
- **Tailwind CSS**

### 🔹 Backend
- **NestJS**
- **WebSockets Gateway**
- **Socket.io**
- **Mongoose**
- **MongoDB Atlas**
- **JWT Authentication**  
  (JSON Web Token – HMAC with SHA-256)
- **TypeScript**
- **DTO-based Folder Structure**


## ⚙️ Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/bhaumik-1910/Realtime-collaborative-document-editing-app-master.git
cd Realtime-collaborative-document-editing-app-master
```
### 2️⃣ Install dependencies

Using **npm**:
```bash
npm install
```

### 3️⃣ Run the development server

Using **npm**:
```bash
npm start
```

### 4️⃣ Preview in browser

```text
http://localhost:3000
```

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👤 Author

**Bhaumik Patel**  
GitHub: [@bhaumik-1910](https://github.com/bhaumik-1910)

---

## ⭐ Support

If you like this project, please give it a ⭐ on GitHub!
