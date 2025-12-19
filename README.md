# MERN Memories Project
will be made soon
A simple full-stack MERN application that allows users to post interesting events that happened in their lives. This project serves as a practical example of building a full-stack application with the MERN (MongoDB, Express, React, Node.js) stack.

## Features

- **Create, Read, Update, and Delete** memories.
- Like posts.
- A clean UI built with Material-UI.

## Tech Stack

- **MongoDB**: NoSQL database for storing memory posts.
- **Express.js**: Back-end framework for building the RESTful API.
- **React.js**: Front-end library for building the user interface.
- **Node.js**: JavaScript runtime for the server-side.
- **Material-UI**: For styling and UI components.
- **Redux**: For state management.

## Project Structure

The project is organized into two main folders:

- `client/`: Contains the front-end React application.
- `server/`: Contains the back-end Express.js API.

---

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- **Node.js** (v14 or newer)
- **npm** (Node Package Manager)
- **MongoDB**: You'll need a MongoDB database. You can get a free one from [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).

### Server Setup

1.  **Navigate to the server directory:**
    ```sh
    cd server
    ```

2.  **Install dependencies:**
    ```sh
    npm install
    ```

3.  **Create an environment file:**
    Create a file named `.env` in the `server` directory and add the following variables.

    ```env
    # The port for the server to run on
    PORT=5000

    # Your MongoDB connection string
    CONNECTION_URL=mongodb+srv://<username>:<password>@your-cluster.mongodb.net/your-database?retryWrites=true&w=majority
    ```
    **Important**: Replace the `CONNECTION_URL` with your actual MongoDB Atlas connection string.

4.  **Start the server:**
    ```sh
    npm start
    ```
    The server will start on `http://localhost:5000`.

### Client Setup

1.  **Navigate to the client directory (from the root):**
    ```sh
    cd client
    ```

2.  **Install dependencies:**
    ```sh
    npm install
    ```

3.  **Start the client:**
    ```sh
    npm start
    ```
    The React development server will start, and your browser should open to `http://localhost:3000`.

---

## Usage

Once both the client and server are running, you can open your browser to `http://localhost:3000` to use the application. Create posts, see the list of memories, and interact with them.

## made with love with someone !!! 
