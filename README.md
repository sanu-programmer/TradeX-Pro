# TradeX-Pro

TradeX-Pro is a full-stack trading dashboard project built with **React** for the frontend/dashboard, **Node.js + Express** for the backend, and **MongoDB** for the database.

---

## Project Structure
Zerodha/
│
├── backend/ # Node.js + Express backend
│ ├── index.js
│ ├── model/
│ ├── schemas/
│ ├── package.json
│ └── .env # MongoDB connection string (ignored in Git)
│
├── dashboard/ # React dashboard (main dashboard UI)
│ ├── public/
│ ├── src/
│ ├── package.json
│ └── .gitignore
│
└── frontend/ # React landing page or public site
├── public/
├── src/
├── package.json
└── .gitignore


---

## Setup Instructions

### Backend
1. Navigate to the backend folder:
```bash
cd backend


Install dependencies:

npm install


Create a .env file with your MongoDB connection string:

MONGO_URL=mongodb+srv://<username>:<password>@cluster0.wi4pryg.mongodb.net/<dbname>?retryWrites=true&w=majority


Start the backend server:

npm start

Dashboard

Navigate to the dashboard folder:

cd dashboard


Install dependencies:

npm install


Start the React dashboard:

npm start


The dashboard will run on http://localhost:3000 (or 3001 if 3000 is busy).

Frontend

Navigate to the frontend folder:

cd frontend


Install dependencies:

npm install


Start the React frontend:

npm start


The frontend will run on http://localhost:3000 (or another available port if 3000 is busy).

