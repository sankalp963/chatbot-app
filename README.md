# ✨ Full Stack Realtime Chat App ✨

## ✨ Features

- 🌟 Tech stack: MERN + Socket.io + TailwindCSS + Daisy UI
- 🔐 Authentication & Authorization with JWT
- � Real-time messaging with Socket.io
- � Online user status
- � Global state management with Zustand
- 🎯 Error handling (both server and client-side)
- 🖼️ Cloudinary image upload support
- 🌓 Light/Dark mode

## 🚀 Running the Application

### 1. Setup Environment Variables
Create a `.env` file in the `backend` directory:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
NODE_ENV=development
```

### 2. Start Backend Server
```bash
cd backend
npm install
npm run dev
```
Backend will run on: http://localhost:5001

### 3. Start Frontend Server
```bash
cd frontend
npm install
npm run dev
```
Frontend will run on: http://localhost:5173
