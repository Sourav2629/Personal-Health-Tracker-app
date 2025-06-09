# Personal-Health-Tracker

A full-stack web application for tracking daily habits, lifestyle scores, and personal challenges. Built with React (Vite) frontend and Node.js/Express backend.

## Features

- Daily lifestyle data tracking (sleep, water intake, activity, etc.)
- Dynamic score and status generation
- Interactive dashboard with XP, scores, and badges
- Personal challenge system
- Weekly activity log with visual charts
- Achievement badge system

## Prerequisites

Before running this project, make sure you have the following installed:
- Node.js (v14 or higher)
- npm (Node Package Manager)

## Tech Stack

- Frontend: React (Vite) with modern JavaScript
- Backend: Node.js with Express.js
- Additional Tools: Chart.js for visualizations, JWT for authentication

## Project Structure

```
Tracker website/
├── frontend/            # React frontend (Vite)
│   ├── src/            # Source files
│   │   ├── components/ # React components
│   │   ├── pages/      # Page components
│   │   ├── context/    # React context
│   │   ├── utils/      # Utility functions
│   │   └── assets/     # Images, styles, etc.
│   └── public/         # Static files
└── backend/            # Node.js backend
    ├── routes/         # API routes
    ├── models/         # Database models
    ├── controllers/    # Route controllers
    ├── middleware/     # Custom middleware
    └── utils/          # Utility functions
```

## Installation

1. Clone the repository:
```bash
git clone <your-repository-url>
cd Tracker\ website
```

2. Install dependencies for both frontend and backend:
```bash
# Install root dependencies
npm install

# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install
```

## Running the Application

1. Start the frontend development server:
```bash
cd frontend
npx vite
```
The frontend will be available at http://localhost:3000

2. In a new terminal, start the backend server:
```bash
cd backend
npm start
```

## Environment Variables

Create `.env` files in both frontend and backend directories:

### Backend `.env`:
```
MONGODB_URI=mongodb://localhost:27017/tracker
JWT_SECRET=your-very-secure-jwt-secret-key
PORT=5000
NODE_ENV=development
# Add other backend environment variables
```

### Frontend `.env`:
```
VITE_API_URL=http://localhost:5000/api
# Add other frontend environment variables
```

## Available Scripts

- Frontend:
  - `npm run dev`: Start development server
  - `npm run build`: Build for production
  - `npm run preview`: Preview production build

- Backend:
  - `npm start`: Start the server
  - `npm run dev`: Start with nodemon (development)


