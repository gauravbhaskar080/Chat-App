# MERN Chat-App Website

This project is a real-time chat application built using the MERN (MongoDB, Express.js, React, Node.js) stack. It allows users to create accounts, join chat rooms, and engage in real-time conversations with other users.

## Table of Contents
- [Features](#features)
- [Demo](#demo)
- [Setup](#setup)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication and authorization system.
- Create and join chat rooms for real-time conversations.
- Send and receive messages instantly within a chat room.
- Notification system for new messages.

## Demo

[Link to Demo](https://gauravbhaskar-chat-app.netlify.app/)

## Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/gauravbhaskar080/Chat-App.git
   ```

2. **Install dependencies:**

   Navigate to the project directory and run:

   ```bash
   cd Chat-App

   cd frontend
   npm install
   cd backend
   npm install
   ```

3. **Set up MongoDB:**

   - Create a `.env` file in the root directory and add your MongoDB URL:

     ```
     MONGO_URI = 'your_mongo_db_url'
     JWT_SECRET = 'your_jwt_secret'
     PORT = 5000
     ```

## Usage

1. **Start the server:**
   
   In a new terminal window, navigate to the `backend` directory and run:

   ```bash
   cd backend
   npm start
   ```

   The server will start at `http://localhost:5000`.

2. **Start the client:**

   In a new terminal window, navigate to the `frontend` directory and run:

   ```bash
   cd frontend
   npm start
   ```

   The client will start at `http://localhost:3000`.

3. **Access the website:**

   Open a web browser and go to `http://localhost:3000`.

## File Structure

- `frontend/`: Contains the React frontend.
  - `public/`: Holds static files like CSS, images, and JavaScript.
  - `src/`: Contains the main source code.
    - `components/`: React components used in the application.
    - `animations/`: Animations used for UI elements.
    - `config/`: Configuration files.
    - `context/`: React context providers.
    - `Pages/`: Different pages of the application.
    - `App.js`: The main application component.
    - `index.js`: Entry point of the React application.
    - `theme.js`: Contains theme-related styling.
- `backend/`: Contains the Node.js backend.
  - `config/`: Configuration files.
  - `controllers/`: Controllers for handling routes and data.
  - `data/`: Sample data for initial setup.
  - `middleware/`: Custom middleware functions.
  - `models/`: Mongoose models for MongoDB.
  - `public/`: Static files.
  - `routes/`: Express.js route handlers.
  - `server.js`: Entry point of the Node.js application.
  - `.env`: Configuration file for environment variables.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your forked repository.
5. Create a pull request to the original repository.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code for your own purposes.

---