Real-time Chat Application (GitHub Repository)
Technologies Used: React, Vite, Node.js, Express.js, MongoDB, Socket.io, WebSockets, JWT Authentication

Project Overview:
Developed a full-stack real-time chat application that allows users to communicate instantly through WebSockets (Socket.io). The application ensures a seamless user experience by integrating React (frontend) with Node.js & Express (backend) while using MongoDB for data storage. Implemented authentication mechanisms to ensure secure login and messaging.

Key Features:
✅ Real-time Messaging: Implemented WebSockets using Socket.io to enable instant, bidirectional communication between users. Messages are delivered and displayed in real time without needing to refresh the page.

✅ User Authentication & Security: Integrated JWT (JSON Web Token) authentication to ensure secure user login and prevent unauthorized access. Used cookie-based authentication for session persistence.

✅ MongoDB Database: Designed and implemented a NoSQL database structure using MongoDB to store user details and chat history efficiently. Used Mongoose ORM for seamless data handling.

✅ Frontend Development (React + Vite):

Developed a responsive and dynamic user interface using React.js.
Used Vite for faster development and optimized builds.
Created a modern UI design for chat screens, login, and user authentication.
✅ Backend Development (Node.js + Express.js):

Built a REST API using Express.js to handle user authentication, message storage, and real-time communication.
Implemented CORS policy to allow secure interaction between frontend (http://localhost:5173) and backend (http://localhost:5000).
Used cookie-parser to manage user sessions.
✅ Deployment & Scalability:

Configured the app to serve the frontend using Express.js in production mode.
Used environment variables (.env) to manage database credentials and API secrets.
✅ Error Handling & Optimizations:

Implemented try-catch blocks and middleware for handling errors gracefully.
Used Eslint and Prettier for code quality and consistency.
Optimized database queries and minimized latency for fast message delivery.
