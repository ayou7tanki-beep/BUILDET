# BUILDET - Builder Marketplace Platform

A modern web platform connecting construction clients with professional builder companies.

## 📋 Project Overview

BUILDET is a marketplace where:
- **Clients** can upload their construction/building projects
- **Builder Companies** can browse projects and submit proposals/accept contracts
- Both parties can communicate and manage projects efficiently

## 🛠️ Tech Stack

### Backend
- **Framework**: Express.js (Node.js)
- **Database**: MongoDB with Mongoose ODM
- **Authentication**: JWT (JSON Web Tokens) + bcryptjs
- **File Uploads**: Multer
- **API**: RESTful API with CORS support

### Frontend
- React-based client (in `/client` directory)

### Development
- Nodemon for hot-reload during development

## 📦 Dependencies

```json
{
  "name": "buildet",
  "version": "1.0.0",
  "description": "A marketplace connecting clients with builder companies",
  "main": "server.js",
  "scripts": {
    "start": "node server.js",
    "dev": "nodemon server.js",
    "client": "cd client && npm start",
    "build": "cd client && npm run build"
  },
  "dependencies": {
    "express": "^4.18.2",
    "mongoose": "^7.0.0",
    "bcryptjs": "^2.4.3",
    "jsonwebtoken": "^9.0.0",
    "dotenv": "^16.0.3",
    "cors": "^2.8.5",
    "multer": "^1.4.5-lts.1"
  },
  "devDependencies": {
    "nodemon": "^2.0.20"
  }
}
