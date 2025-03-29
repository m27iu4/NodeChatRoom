# NodeChatRoom 🗨️

A real-time chat application built with **Node.js**, **Express**, **MongoDB**, **Passport**, and **Socket.IO** as part of the [freeCodeCamp Advanced Node and Express Certification](https://www.freecodecamp.org/learn/).

This app supports local login, GitHub authentication, and real-time chat using websockets.

---

## 🚀 Features

- 🔐 User authentication (Local & GitHub)
- 💬 Real-time chat room using Socket.IO
- 📄 Sessions and login persistence with Passport.js
- 🧩 MongoDB database integration for user management
- 🎨 Clean UI using Pug templates and CSS

---

## 🛠️ Tech Stack

- **Node.js**
- **Express**
- **MongoDB**
- **Passport.js** (local & GitHub strategies)
- **Socket.IO**
- **Pug** (view engine)
- **dotenv**, **bcrypt**, **express-session**

---

## 📷 Screenshots

| Login Page | Chat Room |
|------------|-----------|
| ![Login Screenshot](public/screenshots/login.png) | ![Chat Screenshot](public/screenshots/chat.png) |

> *Optional: Add screenshots to the `/public/screenshots/` folder and update paths above.*

---

## 🔧 Installation

1. **Clone the repo:**

```bash
git clone https://github.com/m27iu4/NodeChatRoom.git
cd NodeChatRoom

Install dependencies:

bash
Copy
Edit
npm install
Set up environment variables:

Create a .env file in the root folder:

env
Copy
Edit
PORT=3000
SESSION_SECRET=yourSecretString
MONGO_URI=yourMongoDbURI
GITHUB_CLIENT_ID=yourGithubClientID
GITHUB_CLIENT_SECRET=yourGithubClientSecret
Start the app:

bash
Copy
Edit
npm start
Visit http://localhost:3000 in your browser.

🧪 Testing
This project includes tests provided by freeCodeCamp for certification. Make sure all tests pass by running the FCC test suite.

📚 Credits
Created as part of the freeCodeCamp Advanced Node and Express Projects.


