# Client Check-In App

A full-stack application for managing client check-ins using barcode scanning.

## Features

- Barcode-based client check-in system
- Admin dashboard for viewing check-in history
- Real-time filtering and search capabilities
- Secure authentication system
- Responsive design

## Tech Stack

- Frontend: React + Vite + TypeScript
- Backend: Node.js + Express + TypeScript
- Database: Firebase
- UI Framework: Chakra UI

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Firebase project setup

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ClientCheckIn-app.git
cd ClientCheckIn-app
```

2. Install dependencies:
```bash
# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install
```

3. Set up environment variables:
   - Copy `.env.example` to `.env` in both `client` and `server` directories
   - Update the variables with your configuration

4. Start the development servers:
```bash
# Start backend server (from server directory)
npm run dev

# Start frontend server (from client directory)
npm run dev
```

5. Open your browser and navigate to `http://localhost:5173`

## Environment Variables

### Frontend (.env)
```
VITE_API_URL=http://localhost:3001
```

### Backend (.env)
```
FIREBASE_PROJECT_ID=your-project-id
FIREBASE_PRIVATE_KEY=your-private-key
FIREBASE_CLIENT_EMAIL=your-client-email
PORT=3001
NODE_ENV=development
CLIENT_URL=http://localhost:5173
```

## Deployment

The application is configured for deployment on Vercel. Set up the following environment variables in your Vercel project settings:

### Frontend
- `VITE_API_URL`: Your backend API URL

### Backend
- `FIREBASE_PROJECT_ID`
- `FIREBASE_PRIVATE_KEY`
- `FIREBASE_CLIENT_EMAIL`
- `PORT`
- `NODE_ENV`
- `CLIENT_URL`

## License

MIT 