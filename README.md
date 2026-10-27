# 💬 iMessage — Full Stack Real-Time Chat App 🚀

A full-stack real-time messaging application built with React, Node.js, Express, MongoDB, Clerk, and Socket.IO. Chat with users in real time with authentication, online presence, media sharing, and customizable themes.

![Demo App](./frontend/public/screenshot-for-readme.png)

---

## ✨ Features

- 💬 Real-time one-to-one messaging
- ⚛️ Responsive frontend built with React and Tailwind CSS
- 🚀 Backend powered by Node.js and Express.js
- 🔐 Authentication with Clerk
- 🗄️ MongoDB database integration
- ⚡ Real-time communication using Socket.IO
- 🟢 Online user presence tracking
- 🖼️ Image and video sharing support
- 🎨 Light and dark mode
- 🖌️ 13 custom wallpapers
- 🌈 11 customizable themes
- ⌨️ Optional keyboard sound effects
- 📤 Media uploads and optimization with ImageKit
- 🔔 Webhook integration
- ⏰ Scheduled tasks using cron jobs
- 🛡️ Express middleware
- 🌐 Deployment using Render
- 📂 Complete source code for learning and customization

---

## 🛠️ Tech Stack

### Frontend
- React
- Vite
- Tailwind CSS
- HeroUI
- Zustand
- Socket.IO Client
- Clerk React

### Backend
- Node.js
- Express.js
- MongoDB
- Socket.IO
- Clerk Express
- ImageKit

### Database & Deployment
- **Database:** MongoDB Atlas
- **Frontend:** Render
- **Backend:** Render
- **Authentication:** Clerk
- **Media Storage:** ImageKit

---

## 📁 Project Structure

```text
IMESSAGE/
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   └── ...
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── lib/
│   ├── package.json
│   └── ...
│
└── README.md
```

---

## ⚙️ Environment Variables

Create a `.env` file inside the `backend` directory:

```env
PORT=your_port
NODE_ENV=development

MONGO_URI=your_mongodb_connection_string

CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
CLERK_WEBHOOK_SIGNING_SECRET=your_clerk_webhook_signing_secret

IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key

FRONTEND_URL=your_frontend_url
```

Create a `.env` file inside the `frontend` directory:

```env
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```

**Important:** Use the exact environment variable names required by your code. Never commit secret keys or `.env` files to GitHub.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Tishajoshi/imessage.git
cd imessage
```

### 2. Install frontend dependencies

```bash
cd frontend
npm install
```

### 3. Install backend dependencies

Open another terminal and run:

```bash
cd backend
npm install
```

### 4. Configure environment variables

Set up MongoDB Atlas, Clerk, and ImageKit. Add the required environment variables to the respective `.env` files.

### 5. Start the backend

From the `backend` directory:

```bash
npm run dev
```

### 6. Start the frontend

From the `frontend` directory:

```bash
npm run dev
```

Open the local URL displayed by Vite in your browser.

*These commands assume your `package.json` files define the `dev` scripts.*

---

## 🌐 Live Demo

🔗 [**Try iMessage Now**](https://imessage-9nvl.onrender.com)

---

## ⭐ Support

If you like this project, consider giving the repository a star!

Built with ❤️ using React, Node.js, Express, MongoDB, and Socket.IO.
