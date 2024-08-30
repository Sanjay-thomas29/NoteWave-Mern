# NoteWave

NoteWave is a powerful, user-friendly note-taking application built with the MERN stack (MongoDB, Express, React, Node.js). Whether you want to jot down quick thoughts, organize your work, or keep track of important information, NoteWave provides a seamless experience for managing your notes efficiently.

## Features

- **Create, Read, Update, Delete (CRUD) Notes**: Perform all the essential note-taking operations with ease.
- **User Authentication**: Secure user registration and login with JWT (JSON Web Token) authentication.
- **Responsive Design**: Access your notes on any device with a fully responsive interface.
- **Real-time Updates**: Experience instant updates as you modify your notes, thanks to real-time data handling.
- **Search Functionality**: Quickly find specific notes using the integrated search feature.
- **Categorization**: Organize your notes by categories to keep everything neatly arranged.

## Tech Stack

- MongoDB: For storing user data and notes.
- Express.js: Backend framework to build the API.
- React.js: Frontend library for building the user interface.
- Node.js: JavaScript runtime environment for the backend.

Getting Started

Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- [Git](https://git-scm.com/)

### Installation

1. Clone the repository:

    bash
    git clone https://github.com/Sanjay-thomas29/NoteWave-Mern.git
    cd NoteWave-Mern
    ```

2. Install dependencies for both client and server:

    bash
    Install server dependencies
    cd server
    npm install

    Install client dependencies
    cd ../client
    npm install
    

3. Set up environment variables:

   Create a `.env` file in the `server` directory with the following variables:

    plaintext
    MONGO_URI=<your-mongodb-uri>
    JWT_SECRET=<your-jwt-secret>
    

4. Start the development server:

    bash
    # Start the backend server
    cd server
    npm run dev

    # Start the frontend server
    cd /client
    npm start
   

5. Open the app:

   Go to `http://localhost:3000` in your browser to start using NoteWave.

## Project Structure

- client: Contains the React frontend.
- server: Contains the Express backend and database configurations.
- models: MongoDB models for users and notes.
- routes: API routes for authentication and note management.

 Contributing

Contributions are welcome! If you have suggestions, feel free to fork the repository and submit a pull request.

License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

 Contact

For any inquiries or support, please reach out to [Sanjay Thomas](mailto:sanjaythomas29@gmail.com).

