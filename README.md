# Smart Stay System

Smart Stay System is a full-stack web application inspired by Airbnb that allows users to explore accommodation listings, create property listings, upload images, and share reviews and ratings. Built using Node.js, Express.js, MongoDB, and EJS, the project demonstrates practical full-stack web development concepts.

## Features

- User authentication (signup, login, and logout)
- Create, edit, and delete property listings
- Upload and display property images
- Browse listings by category
- Add reviews and ratings to listings
- Responsive user interface using EJS, HTML, CSS, and JavaScript
- Error handling and flash messages

## Tech Stack

- **Backend:** Node.js, Express.js
- **Frontend:** EJS, HTML5, CSS3, JavaScript
- **Database:** MongoDB Atlas, Mongoose
- **Authentication:** Passport.js
- **Image Uploads:** Multer, Cloudinary
- **Session Management:** Express-Session, Connect-Mongo
- **Validation:** Joi
- **Version Control:** Git and GitHub

## Project Structure

```text
Smart-Stay-System/
├── controllers/       # Application logic
├── models/            # Mongoose models
├── public/            # CSS, JavaScript, and static assets
├── routes/            # Express routes
├── uploads/           # Uploaded files
├── utils/             # Utility functions and error handling
├── views/             # EJS templates
├── app.js             # Main application entry point
├── cloudConfig.js     # Cloudinary configuration
├── middleware.js      # Custom middleware
├── schema.js          # Input validation schemas
├── package.json       # Project dependencies and scripts
├── package-lock.json  # Dependency lock file
└── .gitignore         # Git exclusion rules
```

## Getting Started

### Prerequisites

- Node.js and npm
- A MongoDB Atlas account or a local MongoDB instance
- A Cloudinary account for image uploads

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/techaadrsh/Smart-Stay-System.git
cd Smart-Stay-System
```

**2. Install dependencies**

```bash
npm install
```

**3. Configure environment variables**

Create a `.env` file in the project root and add the environment variables required by your application.

For example, if your code uses these variable names:

```env
ATLAS_URL=your_mongodb_connection_string
CLOUD_NAME=your_cloudinary_cloud_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret
SECRET=your_session_secret
```

Use the exact variable names referenced in your `app.js` and `cloudConfig.js` files. Keep your `.env` file private and never commit real credentials to GitHub.

**4. Start the application**

```bash
node app.js
```

**5. Open the application**

Visit the following URL in your browser:

http://localhost:8080

## Application Architecture

Smart Stay System follows a modular backend structure:

- **Routes:** Define the application's HTTP endpoints.
- **Controllers:** Handle requests and application logic.
- **Models:** Define database structures and interact with MongoDB.
- **Views:** Render dynamic pages using EJS.
- **Middleware:** Handle reusable request processing, validation, and other application tasks.
- **Cloudinary Configuration:** Supports cloud-based image storage.

## Learning Outcomes

This project provides practical experience with:

- Building server-side applications using Node.js and Express.js
- Implementing CRUD operations with MongoDB and Mongoose
- Creating dynamic pages with EJS
- Managing user authentication and sessions
- Uploading images using Cloudinary
- Organizing code using a modular architecture
- Managing source code with Git and GitHub

## Acknowledgements

Inspired by accommodation-booking platforms such as Airbnb and developed as a full-stack web development learning project.
