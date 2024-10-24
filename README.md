
# MERN Blog Application

![MERN Stack](https://img.shields.io/badge/MERN-Stack-blue?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

A full-stack blog application built using the MERN (MongoDB, Express.js, React, Node.js) stack.

## Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Backend Setup](#backend-setup)
  - [Frontend Setup](#frontend-setup)
- [Running the Application](#running-the-application)
- [Contributing](#contributing)
- [License](#license)

## Features

- 🔐 User authentication (registration/login)
- ✍️ Create, edit, and delete blog posts
- 💬 Commenting system
- 👤 User profiles
- 📱 Responsive design

## Project Structure

```

mern-blog/
├── api/                 # Backend folder
│   ├── models/          # API routes
│   ├── uplaods/         # Post Pictures
│   ├── index.js         # Custom middleware
│   ├── .env             # Environment variables
│   └── .gitignore        # .gitignore
├── client/              # Frontend folder
│   ├── public/          # Public assets
│   ├── src/             # React source files
│   └── package.json     # Frontend dependencies
├── .gitignore           # Git ignore file
├── README.md            # This file
├── package.json         # Project dependencies and scripts
└── yarn.lock            # Dependency versions lock file

```

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- yarn package manager
- MongoDB database

### Backend Setup

1. **MongoDB Setup:**
   - Create a MongoDB database (locally or using [MongoDB Atlas](https://www.mongodb.com/cloud/atlas))

2. **Environment Variables:**
   Create a `.env` file in the `api` folder with the following content:
```

MONGODB_URI=`<your_mongodb_connection_string>`
JWT_SECRET=`<your_jwt_secret_key>`

```
Replace placeholders with your actual MongoDB connection string and a strong JWT secret key.

3. **Install Dependencies:**
```bash
cd api
yarn install
```

4. **Start the Server:**

```shellscript
yarn start
```

The server will typically run on port 5000.




### Frontend Setup

1. **Install Dependencies:**

```shellscript
cd client
yarn install
```


2. **Start Development Server:**

```shellscript
yarn start
```

The React development server will usually start on port 3000.




## Running the Application

1. Ensure both backend and frontend servers are running.
2. Open your web browser and visit [http://localhost:3000](http://localhost:3000).


## Contributing

We welcome contributions to improve the MERN Blog Application! Please follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit them: `git commit -m "Add your feature"`
4. Push to your branch: `git push origin feature/your-feature-name`
5. Open a pull request


Please read our [Contributing Guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
