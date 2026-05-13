# Echo – Real-Time Chat Application

Echo is a full-stack real-time chat application where users can sign up, log in, and chat instantly with other users. It supports live messaging, online user tracking, secure authentication, and persistent chat history.

---

## Features

- User authentication (Signup / Login / Logout)
- Secure password hashing
- JWT-based authentication with cookies
- Real-time messaging using sockets
- Online/offline user status
- One-to-one chat system
- Persistent message storage
- Responsive UI
- Protected routes

---

## Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS
- Zustand
- Context API

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- Socket.IO
- JWT Authentication
- bcryptjs

---

## Project Structure

```bash
Echo/
│
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── socket/
│   ├── utils/
│   └── server.js
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── hooks/
│   │   ├── pages/
│   │   └── zustand/
│
└── README.md
```

---

## Installation

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd Echo
```

---

### 2. Install dependencies

#### Backend

```bash
cd backend
npm install
```

#### Frontend

```bash
cd frontend
npm install
```

---

## Environment Variables

Create a `.env` file inside the backend folder:

```env
PORT=5000
MONGO_DB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
NODE_ENV=development
```

---

## Run the Project

### Start backend

```bash
cd backend
npm run dev
```

### Start frontend

```bash
cd frontend
npm run dev
```

---

## Application Flow

1. User creates an account or logs in.
2. Authentication token is generated and stored securely.
3. User can search and select other users.
4. Messages are sent and received in real time.
5. Online users are tracked using socket connections.
6. Chat history is stored in the database.

---

## Security Features

- Password hashing using bcrypt
- JWT authentication
- Protected API routes
- Cookie-based session handling

---

## Future Improvements

- Group chat
- File/image sharing
- Typing indicators
- Message reactions
- Read receipts
- Voice/video calling

---

## Learning Outcomes

This project helped me strengthen my understanding of:

- REST APIs
- Authentication & authorization
- Real-time communication
- State management
- Database design
- Full-stack application architecture

---

## Author

**Anjali**  
Computer Science Engineering Student  
Backend & Full Stack Developer

