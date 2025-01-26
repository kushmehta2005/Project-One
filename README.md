# Project-One

**Project-One** is a web-based chat system built using the MERN (MongoDB, Express.js, React, Node.js) stack. It allows users to create accounts, send messages in real time, and enjoy a seamless chat experience.

---

## Features

- User authentication (registration, login, logout).
- Real-time messaging using WebSockets (Socket.IO).
- User-friendly chat interface.
- RESTful API for backend operations.
- Responsive design for mobile and desktop users.

---

## File Structure

```plaintext
Project-One/
├── server/
│   ├── config/         # Database and environment configuration
│   ├── controllers/    # API controllers
│   ├── models/         # Mongoose models
│   ├── routes/         # API routes
│   ├── server.js       # Entry point for the server
│   └── package.json    # Server dependencies
├── client/
│   ├── public/         # Static assets
│   ├── src/
│   │   ├── components/ # Reusable React components
│   │   ├── pages/      # Page-level components
│   │   ├── services/   # API service functions
│   │   ├── App.js      # Main React app
│   │   └── index.js    # React entry point
│   └── package.json    # Client dependencies
├── README.md            # Project documentation
├── .env                 # Environment variables
└── .gitignore           # Ignored files for Git
```

---

## Prerequisites

Ensure you have the following installed:

- Node.js (v14+)
- npm or yarn
- MongoDB (running instance)

---

## Installation

Follow these steps to get started:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/Project-One.git
   cd Project-One
   ```

2. **Server setup**:
   ```bash
   cd server
   npm install
   ```

3. **Client setup**:
   ```bash
   cd ../client
   npm install
   ```

4. **Environment variables**:
   - Create a `.env` file in the `server` directory with the following variables:
     ```plaintext
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     PORT=5000
     ```
   - Create a `.env` file in the `client` directory with the following variable:
     ```plaintext
     REACT_APP_API_URL=http://localhost:5000
     ```

---

## Running the Application

1. **Start the server**:
   ```bash
   cd server
   npm start
   ```

2. **Start the client**:
   ```bash
   cd ../client
   npm start
   ```

The application will be available at [http://localhost:3000](http://localhost:3000).

---

## Useful Links

- [MongoDB Documentation](https://www.mongodb.com/docs/)
- [Express.js Documentation](https://expressjs.com/)
- [React Documentation](https://reactjs.org/docs/)
- [Node.js Documentation](https://nodejs.org/en/docs/)
- [Socket.IO Documentation](https://socket.io/docs/)

---

## Contribution

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).
