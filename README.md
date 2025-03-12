# AeroInk

AeroInk is a full-stack web application built with Node.js, Express, MongoDB, and modern frontend tools.
## Features

- User authentication (login/signup) using JWT.
- RESTful API for managing [describe your project's main functionality].
- Modern frontend built with [mention the frontend framework/library, e.g., React, Vue, etc.].
- MongoDB for database management.

## Prerequisites

Before running the project, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/) (usually comes with Node.js)
- [MongoDB](https://www.mongodb.com/) (local or cloud instance)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Priyanshu762/AeroInk.git
   cd AeroInk
2. **Install Dependencies:**

   Navigate to the root directory and install the required dependencies for both the server and client:
   ```bash
   npm install
   cd client
   npm install
3. **Setup Environment Variables:**
   
   Create a .env file in the server directory and add the following variables:
   ```bash
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
4. **Start the development server:**

   Run the following command to start both the backend and frontend servers simultaneously:
   ```bash
   npm run dev