# Blogging Website

This project is a full-stack blogging website built using React, JavaScript, HTML, and Tailwind CSS for the front-end, and custom Node.js backend services for authentication, configuration, and file upload. The application allows users to sign up, log in using email and password authentication, create and publish blog posts with text and images, and sign out securely.

## Features

- **User Authentication**: Sign up and log in securely using email and password.
- **Blog Creation**: Write and publish blog posts with text content and uploaded images.
- **Image Upload**: Utilize Multer and Cloudinary for image upload and storage.
- **Custom Backend Services**: Implement custom authentication and configuration services using bcrypt for password encryption and JWT for secure token-based authentication.
- **Responsive Design**: Mobile-friendly user interface designed with Tailwind CSS.

## Technologies Used

### Frontend
- **React**: JavaScript library for building user interfaces.
- **Tailwind CSS**: Utility-first CSS framework for styling the frontend.
- **HTML/CSS**: Markup and styling for the user interface.

### Backend
- **Node.js**: JavaScript runtime for building the backend server.
- **Express.js**: Web framework for handling backend routes and requests.
- **MongoDB**: NoSQL database for storing user data and blog posts.
- **bcrypt**: Library for password hashing.
- **JWT (JSON Web Tokens)**: For secure authentication and authorization.
- **Multer**: Middleware for handling file uploads.
- **Cloudinary**: Cloud-based media management platform for image storage and management.

## Getting Started

To run this project locally, follow these steps:

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/KnightSoul9/Blogging_Website.git
   cd Blogging_Website
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the frontend development server:
   ```bash
   npm run build
   ```


3. Set up environment variables:
   - Create a `.env` file in the backend directory.
   - Define environment variables for MongoDB connection URI, JWT secret key, Cloudinary credentials, etc.

   Example `.env` file:
   ```plaintext
   MONGODB_URI=your_mongodb_connection_uri
   JWT_SECRET=your_jwt_secret_key
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   ```

4. Start the backend server:
   ```bash
   npm run build
   ```

## Usage

1. Open the application in your web browser (`http://localhost:3000` by default).
2. Sign up for a new account using your email and password.
3. Log in to access the dashboard and create new blog posts.
4. Write and publish blog posts by adding text content and uploading images.
5. Log out securely when finished.

## Custom Backend Services

The backend services have been custom-built to handle user authentication and blog post management:

- **Authentication Service**: Implements user signup, login, and logout using bcrypt for password hashing and JWT for token-based authentication.
- **Configuration Service**: Manages environment variables and configuration settings for the backend.
- **Blog Post Service**: Handles creation, retrieval, and storage of blog posts, including text content and uploaded images.

## Deployment

This application can be deployed to cloud platforms like Heroku, Vercel, or AWS. Make sure to set up environment variables for production deployment to ensure security and proper functionality.

## License

This project is licensed under the [MIT License](LICENSE).

---

**Author**: Your Name  
**Contact**: your.email@example.com  
**Project Link**: [GitHub](https://github.com/KnightSoul9/Blogging_Website)

Enjoy blogging with your custom-built platform! 📝🌟
