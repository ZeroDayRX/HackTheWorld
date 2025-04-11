# Hack The World
A hacking simulation game where players manage virtual machines, discover other players' IPs, perform hacking attempts, and generate virtual coins over time.

Site inspired by the old Hacker Experience, developed as a way to learn React and Node.js.
This project was created as a hands-on approach to study and apply core concepts of modern web development, including:
  - Front-end with React
  - Back-end with Node.js
  - Client-server integration
  - Full stack development practices
The main goal is to recreate the experience of the original site while deepening my knowledge of the technologies used.

## Project Structure

This project is divided into two parts:

- **Frontend**: React Application
- **Backend**: Node.js API with Express

## Requirements

### General Requirements
- Node.js v18.0.0 or higher
- npm v9.0.0 or higher (or yarn)
- MongoDB 5.0 or higher

### Frontend (React)
- React 18
- React Router Dom 6
- Axios
- Styled Components

### Backend (Node.js)
- Express
- Mongoose
- JWT (jsonwebtoken)
- bcryptjs
- cors
- dotenv

## Installation

### Setting up the Backend

```bash
# Clone the repository
git clone https://github.com/ZeroDayRX/HackTheWorld.git
cd hack-the-world-api

# Install dependencies
npm install

# Configure environment variables
cp .env.example .env
# Edit the .env file with your settings

# Start development server
npm run dev
```

### Setting up the Frontend

```bash
# In the project root
cd hack-the-world

# Install dependencies
npm install

# Start React application
npm start
```

<!-- ## Features

- Authentication system (login/register)
- Customizable virtual machines with technical specifications
- Fictional IP system for each machine
- IP discovery and hacking mechanics
- Virtual coin generating programs
- Store for upgrades and purchases -->

## Development

### Available Backend Scripts
- `npm start`: Starts the Node.js server
- `npm run dev`: Starts the server with nodemon (automatic restart)

### Available Frontend Scripts
- `npm start`: Starts the React development server
- `npm run build`: Creates the production build
- `npm test`: Runs tests
