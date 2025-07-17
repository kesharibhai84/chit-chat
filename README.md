# Chit-Chat 💬

A real-time chat application built with MERN stack and Socket.io

## Features 🚀

- Real-time messaging
- User authentication
- Group chat creation
- One-on-one chat
- User profile management
- Real-time typing indicators
- Online/offline status
- Message notifications
- Responsive design

## Tech Stack 💻

- **Frontend:** React, Chakra UI
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Real-time Communication:** Socket.io
- **Authentication:** JWT
- **File Upload:** Cloudinary

## Installation 🛠️

1. Clone the repository
```bash
git clone https://github.com/kesharibhai84/chit-chat.git
cd chit-chat
```

2. Install dependencies
```bash
# Install backend dependencies
npm install

# Install frontend dependencies
cd frontend
npm install
```

3. Configure environment variables
```bash
# Create .env file in root directory
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
NODE_ENV=development
```

4. Run the application
```bash
# Run backend and frontend concurrently
npm start

# Run frontend only
cd frontend
npm start
```

## API Endpoints 🔗

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/user` | Register user |
| POST | `/api/user/login` | Login user |
| GET | `/api/user` | Search users |
| POST | `/api/chat` | Create/Access one-to-one chat |
| POST | `/api/chat/group` | Create group chat |
| PUT | `/api/chat/rename` | Rename group |
| PUT | `/api/chat/groupadd` | Add user to group |
| PUT | `/api/chat/groupremove` | Remove user from group |

## Screenshots 📸

[Add your application screenshots here]

## Contributing 🤝

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



## Author ✨

**Vishal Keshari**
- GitHub: [@kesharibhai84](https://github.com/kesharibhai84)

## Acknowledgments 🙏

- Socket.io Documentation
- MongoDB Documentation
- React Documentation
- Chakra UI Components


