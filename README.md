# 365 Days Goal Tracker (Life Calendar App)

A MERN stack project providing a visual 365 days grid to track daily goals, progress, and maintain a highly productive system.

## Features
- **365 Days Grid**: View the entire year at a glance.
- **Goal Management**: Add, complete, and track goals on a per-day basis.
- **Reschedule**: Easily move uncompleted goals to a future date.
- **Progress Tracking**: Dynamic progress bar calculating completed goals vs total goals.
- **Authentication**: Secure login/signup system with JWT.

## Setup Instructions

### Prerequisites
- Node.js installed
- MongoDB installed and running locally on port 27017 (or update the `MONGO_URI` in `server/.env`).

### 1. Start the Backend Server
```bash
cd server
npm install
npm run dev
```
*(The server will run on http://localhost:5000)*

### 2. Start the Frontend Application
```bash
cd client
npm install
npm run dev
```
*(The Vite app will likely run on http://localhost:5173)*

### Usage
- Open the frontend URL in your browser.
- Create an account.
- Start clicking on days in the calendar grid to add goals!
- Theme utilizes a sleek Black/White/Gray finish with Pastel Green (Completed), Yellow (Pending), Red (Overdue) functionality.
