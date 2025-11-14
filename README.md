# Timeout

_A Full-Stack Web Application Project (Hochschule Koblenz)_

Timeout is a full-stack web application developed as a university project at **HS Koblenz** in collaboration between **Achraf Bennani** and **Juve33**.  
The project demonstrates the integration of a modern JavaScript front-end with a secure, modular Node.js back-end and a MongoDB database.

---

## 🚀 Features

### Front-End

- Built with **React**
- State management using **Redux Toolkit**
- Routing via **React Router**
- Responsive and modular component structure

### Back-End

- **Node.js** + **Express.js** REST API
- **JWT authentication** (access + refresh tokens)
- Rate limiting (`express-rate-limit`)
- Error handling with `express-async-handler`
- CORS, bcrypt, cookie-parser, dotenv
- Clean separation of routes, controllers, and middleware

### Database

- **MongoDB** with **Mongoose**
- Auto-increment fields using `mongoose-sequence`
- Environment-based configuration via `config.env`

---

## 🛠 Tech Stack

| Layer        | Technology                         |
| ------------ | ---------------------------------- |
| Front-end    | React, Redux Toolkit, React Router |
| Back-end     | Node.js, Express.js, JWT, dotenv   |
| Database     | MongoDB + Mongoose                 |
| Languages    | JavaScript, CSS, HTML              |
| Architecture | Client–Server, REST API            |

Repository language statistics:

- **JavaScript:** ~69.5%
- **CSS:** ~29.1%
- **HTML:** ~1.4%

---

## 🎯 Purpose of the Project

This project was created to:

- Learn **full-stack web development**
- Implement **secure authentication**
- Understand **client–server communication**
- Practice **state management** and modular architecture
- Collaborate effectively in a real project environment

The codebase provides a solid foundation for further learning and is useful for academic work, portfolios, and future extensions.

---

## 📁 Project Structure

```bash
timeout/
│
├── client/ # React front-end
│ ├── src/
│ ├── public/
│ └── package.json
│
└── server/ # Express back-end
├── controllers/
├── middleware/
├── models/
├── routes/
├── config.env (your own)
└── package.json
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/juve33/timeout.git
```

### 2. Install server dependencies

```bash
cd timeout/server
npm install
```

### 3. Create environment file

```bash
Create server/config.env:
DATABASE_URI=your_mongodb_connection_string
ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret
PORT=5000
```

### 4. Start the back-end

```bash
npm start
```

### 5. Install client dependencies

```bah
cd ../client
npm install
```

### 6. Start the front-end

```bash
npm start
```

### 7. Open the app

Visit:
http://localhost:3000

### 🤝 Collaboration

This project was developed jointly by:

- Achraf Bennani
- Juve33
  Both contributors worked on different parts of the system (front-end, back-end, routing, UI, authentication) and collaborated using Git.

### 🧱 Possible Future Enhancements

- Role-based authorization (Admin / User)
- UI redesign using Tailwind or Material UI
- Add API documentation (Swagger)
- Deployment on AWS, Render, or Docker
- Add integration & unit tests
- Improve logging and monitoring
- Add caching (Redis) and pagination for scaling
- Convert to TypeScript

### 📌 Why This Project Matters

Timeout demonstrates:

- Modern full-stack development skills
- Secure authentication principles
- Clean architecture and best practices
- Collaboration between two developers
- A foundation that can grow into a production-ready system

It is ideal as:

- A portfolio project
- A university submission
- A template for future applications

### 📄 License

This project is for educational purposes. Add a custom license if needed.
