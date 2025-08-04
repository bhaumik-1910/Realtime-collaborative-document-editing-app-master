
INTRODUCTION -
--------------------------------------------------------------------------------------------------------
In today's interconnected world, seamless collaboration on documents among multiple users is 
essential for productivity and efficiency. The Real-Time Collaborative Document Editor is a 
cutting-edge application designed to facilitate simultaneous editing of shared documents by 
multiple users in real time. This project harnesses the power of modern web technologies, 
including NestJS for the backend, WebSocket for real-time communication, and robust 
authentication mechanisms to ensure data security and user privacy


KEY-FEATURES ->
--------------------------------------------------------------------------------------------------------

  1. Real-Time Collaboration
  2. Document & users management
  3. Identification/mapping of websocket client with database user
  4. Authentication & Authorization
  5. Conflict Resolution
  6. Persistence
  7. Maintaining DTO’s (Data Transfer Object)
  8. Class-Validator & Class-Transformer

TECHNOLOGY STACK  ->
--------------------------------------------------------------------------------------------------------

  1. Frontend : ReactJS, state management(ContextAPI), TailwindCSS
  2. Backend : NestJS, WebSockets Gateway, Socket.io-client, Mongoose, Mongo-Atlas, JWT(JSON web token - HMAC with SHA-256), Typescript

PROJECT STRUCTURE ->
--------------------------------------------------------------------------------------------------------

Realtime-collaborative-doc-editor/
│
├── src/
│ ├── app.module.ts // Main module
│ ├── document/ // Document module
│ │ ├── document.controller.ts // Document controller
│ │ ├── document.service.ts // Document service
│ │ ├── document.entity.ts // Document entity (Mongoose)
│ │ └── document.module.ts // Document module definition
│ │
│ ├── auth/ // Authentication module
│ │ ├── auth.controller.ts // Auth controller (login, register)
│ │ ├── auth.service.ts // Auth service (JWT authentication)
│ │ └── auth.module.ts // Auth module definition
│ │ └── jwt.strategy.ts 
│ │ └── guards
│ │ ├── jwt-guards.auth.ts // JWT guard for authentication
│ │
│ ├── user/ // User module
│ │ ├── user.controller.ts // User controller
│ │ ├── user.service.ts // User service
│ │ ├── user.entity.ts // User entity (Mongoose)
│ │ └── user.module.ts // User module definition
│ ├── socket.gateway.ts // WebSocket gateway
│ │
│ └── main.ts // Entry point for the application
├── .env // Environment variables
└── package.json // Project dependencies and scripts

