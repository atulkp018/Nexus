# Nexus (A Full-Stack MERN Threads & Chat Application)

This project is a comprehensive social media and chat platform built with the MERN stack, integrating real-time messaging and interactive features. The application allows users to engage with posts, communicate via chat, and manage their accounts effectively.

## 🚀 Features

- **Tech Stack**: MERN (MongoDB, Express.js, React.js, Node.js) + Socket.io + Chakra UI
- **User Authentication & Authorization**: Secured with JWT
- **Post Management**: Users can create, delete, like/unlike posts, and add comments
- **User Interaction**: Follow/unfollow functionality to connect with other users
- **Account Control**: Option to freeze/unfreeze an account
- **Dark/Light Mode**: Switch between themes for better user experience
- **Fully Responsive Design**: Optimized for both desktop and mobile views
- **Real-Time Chat**: Supports text and image-based messaging
- **Message Status**: Seen/unseen indicators for chat messages
- **Notification Sounds**: Audio alerts for interactions
- **Seamless Deployment**: Easily deployable with free hosting solutions

## 🛠️ Getting Started

### 1️⃣ Clone the repository
```shell
git clone https://github.com/yourusername/repo-name.git
cd repo-name
```

### 2️⃣ Install dependencies
```shell
npm install
```

### 3️⃣ Setup environment variables
Create a `.env` file in the root directory and add the following configuration:
```ini
PORT=your_port_number
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

### 4️⃣ Build the app
```shell
npm run build
```

### 5️⃣ Start the server
```shell
npm start
```

## 📌 Additional Notes
- The frontend is built using React with Chakra UI for a modern and accessible design.
- WebSockets (via Socket.io) enable real-time interactions and messaging.
- MongoDB is used for efficient data storage and retrieval.
- Users can engage with posts and communicate seamlessly in real time.
- The application is structured for scalability and future enhancements.

Feel free to fork, modify, and contribute to this project! 🚀

