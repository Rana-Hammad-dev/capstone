# Capstone Project

This is my full-stack capstone project, developed as part of my software development internship.

## Tech Stack

- Frontend: React.js
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JWT
- Styling: Tailwind CSS
- Version Control: Git & GitHub

## Project Goal

The goal of this capstone is to build a practical full-stack application while following real-world software development practices.

## Getting Started

These steps assume a typical MERN layout (React frontend, Express backend, MongoDB). Adjust folder names if yours differ.

**Prerequisites**

- Node.js 18 or later
- npm
- MongoDB (local instance or [MongoDB Atlas](https://www.mongodb.com/atlas))
- Git

**Local setup**

1. Clone this repository and open the project root.
2. Install dependencies for both the frontend and the backend (`npm install` in each app directory).
3. Create a backend `.env` file (do not commit it) with at least:
   - `MONGO_URI` — MongoDB connection string
   - `JWT_SECRET` — secret used to sign authentication tokens
   - `PORT` — API port (optional; use the value your server expects)
4. Start MongoDB if you are running it locally.
5. Start the Express API, then start the React development server.

Open the frontend URL printed in the terminal (often `http://localhost:3000`) and confirm the API is reachable on its configured port.

## Development

This project follows an AI-assisted development workflow and uses Git for version control.