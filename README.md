# elib
 rest-api-for-an-elib-app

# E-Library App

A scalable and feature-rich e-library application built with Node.js, Express, and MongoDB. This application allows users to register, log in, and manage a collection of books, with secure authentication and efficient file handling.

## Features

- User registration and login with JWT authentication
- CRUD operations for book resources
- Image upload with Multer and Cloudinary integration
- Secure error handling and CORS configuration
- Temporary file deletion after upload

## Technologies Used

- Node.js
- Express
- MongoDB
- Mongoose
- JWT
- Cloudinary
- Multer
- Nodemon
- ESLint
- Prettier

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/elibrary-app.git
   cd elibrary-app
   ```
2. Install dependencies
   ```
   npm install
    ```
3. Create a .env file and add your environment variables
    ```bash
   PORT=3000
   MONGO_URI=your-mongodb-uri
   JWT_SECRET=your-jwt-secret
   CLOUDINARY_CLOUD_NAME=your-cloudinary-cloud-name
   CLOUDINARY_API_KEY=your-cloudinary-api-key
   CLOUDINARY_API_SECRET=your-cloudinary-api-secret
    ```
    



